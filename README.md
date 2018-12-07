Technoknights 

Une image Docker d’une application Angular qui permet de gérer un ensemble des évènements à travers une calendrier.

Cette image est basée sur node:11.3.0:
@angular/cli@7.1.1


Etape de construction :

1- Nous avons créé une application Angular, vous pouvez consulter le code source de l'application à partir de repository 
https://github.com/teheniGrine/technoknights

2- Créer les fichiers :
	-Dockerfile (https://hub.docker.com/r/teheni/technoknights/~/dockerfile/)
	-.dockerignore

3- Faire docker build –t  teheni/technoknights .
4- Faire docker push teheni/technoknights


 
Installation de l’application 


1- Vous pouvez exécuter docker pull et docker run
docker pull teheni/technoknights
docker run -rm -it -p 127.0.0.1:4200:4200 teheni/technoknights

2- Aller vers l'url http://localhost:4200






