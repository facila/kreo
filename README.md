# facila kreo : Utilitaire de gestion de projets

    Version Beta Test
    
    version : beta 1.00 - Septembre 2022
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
- sh kreo-main/install.sh kreo.b1.00.tar.gz

si la variable globale $FACILA n'existe pas
- elle est créée dans ~/.bashrc : "export FACILA=~/facila"

si il y a une ancienne version de kreo
- les répertoires et fichiers de install_kalkulo sont copiés dans $FACILA/share/save//old

kreo-main.zip     est déplacé dans $FACILA/share/save/install
kreo.b1.00.tar.gz est déplacé dans $FACILA/share/save/version
```
