# facila kreo : Utilitaire de gestion de projets
    
    version : beta 1.00 - Janvier 2023
    auteur  : Thierry LE GALL 
    contact : facila@gmx.fr
    site    : https://github.com/facila/kreo

### Installation de facila kreo
```
vous devez avoir installé au préalable :
- perl et perl-tk ( Tk.pm )

téléchargez kreo à partir de github :
- cliquez sur : Code
- cliquez sur : Download ZIP

l'installation se fait dans le répertoire de l'utilisateur
tapez les commandes suivantes :
- DIR_SOURCE="nom du répertoire où se trouve le fichier téléchargé : kreo-main.zip"
- cd
- mv $DIR_SOURCE/kreo-main.zip .
- unzip kreo-main.zip
- sh kreo-main/install.sh kreo.v1.00.tar.gz

si la variable globale $FACILA n'existe pas
- elle est créée dans ~/.bashrc : "export FACILA=~/facila"

si il y a une ancienne version de kreo
- les répertoires et fichiers de install_kreo sont copiés dans $FACILA/share/save/old

kreo-main.zip     est déplacé dans $FACILA/share/save/install
kreo.v1.00.tar.gz est déplacé dans $FACILA/share/save/version
```

### Utilisation de facila kreo
```
$FACILA/kreo/prg/kreo
```
### L'utilisateur peut créer un alias dans .bashrc
```
alias kreo='$FACILA/kreo/prg/kreo'
```
### La commande devient alors
```
kreo
```
### Application partagée , commandes à faire en root
```
si vous souhaitez partager kreo à un groupe d'utilisateurs vous devez :
- créer un groupe pour kreo ou utiliser un groupe déjà existant
- mettre les répertoires et fichiers de kreo dans ce groupe ( vérifier les droits r-x )
- créer les utilisateurs en les mettant dans ce groupe

les utilisateurs doivent se connecter au serveur avec la commande : ssh -X SERVEUR
```
