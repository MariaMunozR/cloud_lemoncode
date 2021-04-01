#Modulo Cloud - Laboratorio
#Básico
Desplegar en Github Pages de forma manual:

Tenemos un repo en Github.
Queremos desplegar una página de demo.
Realizar el despliegue manual.
Automatizar el proceso de despliegue:

Queremos que cada vez que se haga un merge a master se dispare un flujo de build y despliegue.
Usar Github Actions para esto.

· Acciones
Inicio
npm install
Gh pages
npm install gh-pages --save-dev
SSH-KeyGen
ssh-keygen -m PEM -t rsa -C "cd-user@my-app.com"