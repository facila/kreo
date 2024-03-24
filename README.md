# facila kreo : Utilitaire de gestion de projets
    
    version : 1.20 Mars 2024
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
  MAIN=kreo-main
  TAR=kreo.v1.20.tar.gz
  DIR="nom du répertoire où se trouve le fichier téléchargé : $MAIN.zip"
  cd
  mv $DIR/$MAIN.zip .
  unzip $MAIN.zip
  sh $MAIN/install.sh $TAR

si la variable globale $FACILA n'existe pas
- elle est créée dans ~/.bashrc : "export FACILA=~/facila"

si il y a une ancienne version de kreo
- les répertoires et fichiers de install_kreo sont copiés dans $FACILA/save/old

$MAIN.zip est déplacé dans $FACILA/save/install
$TAR      est déplacé dans $FACILA/save/version
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
### Paramètres de kreo
```
Vous devez configurer les paramètres de kreo
Voir Aide - Kreo - Paramètres
```
### Application partagée sur un serveur
```
kreo est accessible à tous les utilisateurs ayant un compte sur le serveur
avec les droits r-x ou r-- pour tous
les utilisateurs doivent se connecter au serveur avec la commande : ssh -X SERVEUR
```
