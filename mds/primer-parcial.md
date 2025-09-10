# Examen Primer Parcial

#### 1. ¿Qué es y para qué sirve Visual Studio Code?
Es un editor de codigo donde podemos programar con diferentes lenguajes como js,html,css, etc. Te apoya bastante incluso para completar parte del codigo que estes escribiendo. 
#### 2. ¿Qué es y para qué sirve la Terminal de Comandos?
Es para escribirle practicamente instrucciones al sistema y poder trabajar con Git
#### 3. ¿Qué es y para qué sirve Markdown?
Es para darle algun formato al texto
#### 4. ¿Qué es y para qué sirve Git?
Es un sistema que te ayuda a llevar registro de todos los cambios que vas haciendo en tu proyecto local
#### 5. ¿Qué es y para qué sirve GitHub?
Es una plataforma que ayuda a guardar cualquier proyecto en repositorios en la nube. Tambien es una muy buena herramienta para hacer trabajos en colaboracion porque les permite a todos ir subiendo los cambios desde sus computadoras y que los demas vean en tiempo real cuando se actualiza y que es lo que actualizo tu equipo
#### 6. ¿Para qué sirven los siguientes comandos: pwd, whoami, touch, mkdir, cp, mv, ls, clear, cd y rm?
```bash
pwd te muestra en que archivo te encuentras en ese momento
whoami te dice el usuario que se esta usando
touch crea un archivo vacio 
mkdir crea una carpeta vacia 
cp copia el archivo o carpeta que pongas
mv mueve el archivo o carpeta que pongas
ls lista los archivos que existen en el lugar donde estes
clear limpia la terminal 
cd cambia a la carpeta que pongas
rm elimina archivos
```
#### 7. ¿Qué significan los siguiente caracteres en la terminal de Comandos: ./, ../, /, y ~?
```bash
. representa la carpeta actual
.. representa la carpeta de antes o la principal
/ te lleva a la raiz 
~ te lleva a tu carpeta personal que seria como tu home
```
#### 8. ¿Cómo se inicializa un repositorio en Git?
```bash
git init
```
#### 9. ¿Cómo creas un repositorio en GitHub?
Desde la pagina de GitHub entras a tu perfil y le das a donde dice repositorios, arribita a la derecha hay un cuadradito verde que dice NEW y ya solo le das un nombre y Create repository.
#### 10. ¿Cómo vinculas un repositorio local de Git con uno remoto en GitHub?
Creas tu repositorio local y luego en la terminal ya despues de haber inicializado y haber hecho un commit para que se refleje ponemos 
```bash
git remote add origin (el link que te aparece en tu github de tu repositorio)
git push -u origin main
```

#### 11. ¿Cuál es el flujo básico de trabajo en Git y GitHub?, explicalo indicando la secuencia de comandos.
```bash
git init
git add .
git commit -m "un commit"
git push
```

#### 12. ¿Para qué sirve el archivo .gitignore?
Sirve para que git ignore las extensiones que nosotros indiquemos.
#### 13. ¿Cuál es el propósito de una rama?
Pues en si es para hacer cambios o implementaciones sin afectar la rama principal y una vez que estas seguro que funciona como querias ya inlcluso puedes fusionarlos despues
#### 14. ¿Qué es una fusión?
Es cuando se juntan dos ramas y se pueden complementar una con la otra, cada que fusionas algo te pregunta que es lo que quieres con esta fusion para que funcione exactamente como necesitas
#### 15. Explica los diferentes tipos de fusión que existen.
``` bash
fast-forward avanza y se hace la fusion automaticamente
manual merge la fusion se hace manual para evitar duplicados y escoger la version que quieres conservar
```
#### 16. ¿Cómo puedes ver el historial de tu repositorio?
```bash
git log
git log --oneline
```
#### 17. ¿Cuál es el propósito de una etiqueta?
Poder tener ordenado tu GitHub con las distintas versiones que vas haciendo, osea las distintas actualizaciones y funcionalidades que vas agregando y la gente pueda descargar esa nueva version ahi directamente con el link.