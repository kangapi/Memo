# Crée un nouveau serveur
## Créer le dossier 
``sudo mkdir [nom du dossier]``
## Se déplaver dans le dossier
``cd [le dossier]``
## Télécharger Build Tool
``sudo wget https://hub.spigotmc.org/jenkins/job/BuildTools/lastSuccessfulBuild/artifact/target/BuildTools.jar``
## Installer la version voulue
``sudo java -Xmx1024M -jar BuildTools.jar --rev [numero de version]``
[Liste de toutes les versions](https://www.spigotmc.org/wiki/buildtools/)
## Lancer la version
``sudo java -Xmx[ram max en G ou M] -jar /home/minecraft/spigot-[version].jar nogui``
## Accepter les conditions d’utilisation
``sudo sed -i 's/false/true/g' eula.txt```
