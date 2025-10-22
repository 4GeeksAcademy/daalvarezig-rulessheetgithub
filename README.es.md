En esta clase hemos estado hablando sobre los comandos que mas utilizamos y las Best Practices.

Como Best practipe principal deberiamos serguir la regla:

SI NO TE TOCA, NO TOQUES

Una vez que nos centramos en lo que nos toca:

Antes de un push, haz un Pull

Con estas dos primeras reglas, deberíamos estar principalmente en nuestro trabajo.

Los comandos que mas he utilizado ultimamente, a parte de los siempre habituales:

git add .
git commit -m "Actualización"
git push origin main

Últimamente he descubierto comandos nuevos que he estado usando en otros proyectos como:

git push origin main --force 	-> cuando sabes que los cambios que tienes en local, son los buenos
git add index. html		-> para añadir un archivo en remoto
git status			-> te indica en que rama estas
git remote -v			-> para saber en que proyecto estoy realmente

Y en la clase de hoy hemos descubierto, como crear una nueva rama y cambiarte a ella:

git checkout -b "nombre de la rama a crear"

O como cambiar entre las distintas ramas existentes:

git checkout "nombre de la rama a la que queremos ir"

Ademas del comando mas importante que debemos realizar, siempre antes de empezar a trabajar y cada vez que 
vayamos a lanzar un push

git pull origin develop(por ejemplo)


