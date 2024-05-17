Voici une version améliorée et professionnelle du README pour votre projet "Boîte à outils Alex", sans les emojis :

---

# Boîte à outils Alex

Boîte à outils Alex est un outil permettant d'effectuer des scans automatisés sur une cible, comprenant de nombreux outils relatifs au pentest, à l'équipe rouge et à l'équipe bleue.

### Fonctionnalités principales

- Effectuer un scan web
- Générer un rapport de vulnérabilité PDF sur une cible, avec des recommandations

## Installation

### Prérequis

Assurez-vous d'avoir Python 3 installé. Vous pouvez le télécharger à partir de ce lien : [Télécharger Python](https://www.python.org/downloads/). Ou utilisez les commandes suivantes :

```sh
sudo pip update
sudo pip install python3-pip
```

### Téléchargement du projet

Vous pouvez télécharger la version zip depuis GitHub ou cloner le dépôt via la ligne de commande :

```sh
git clone https://github.com/Marlottony/Toolbox-Alex
```

Après le téléchargement, changez de répertoire et installez les bibliothèques nécessaires pour exécuter le script correctement :

```sh
cd pentest-toolbox-alex/
pip install -r requirements.txt
```

## Utilisation

Lancez simplement le script avec Python sans aucun paramètre :

```sh
python pentest-toolbox-alex.py
```

Ensuite, choisissez une option et interagissez avec le menu.

```
 _____        _ _              _____ _         
|_   _|__ ___| | |_ ___ _ _   |  _  | |___ _ _ 
  | || . | . | | . | . |_'_|  |     | | -_|_'_|
  |_||___|___|_|___|___|_,_|  |__|__|_|___|_,_|

 ************************************     
 
    [ 1 ] - Reconnaissance                                                                  
    [ 2 ] - Balayage
    [ 3 ] - Exploitation
    [ 4 ] - OSINT
    [ 5 ] - Générer un rapport PDF sur la cible
    [ 6 ] - Générer une commande de shell inversé
```

### Sous-menus

#### [ 1 ] - Reconnaissance

- [ a ] - Requête Whois de base
- [ b ] - Rechercher un CVE
- [ c ] - Obtenir des données DNS sur un domaine
- [ d ] - Obtenir des informations sur un certificat HTTPS
- [ e ] - Extraire toutes les identifications CVE d'une URL spécifique
- [ z ] - Retour

#### [ 2 ] - Balayage

- [ a ] - Scan de ports Nmap
- [ b ] - Scan Nikto
- [ c ] - Découverte d'URL avec Dirbuster
- [ z ] - Retour

#### [ 3 ] - Exploitation

- [ a ] - Recherche de vulnérabilités et d'exploits sur un service
- [ z ] - Retour

#### [ 4 ] - OSINT

- [ a ] - Recherche de noms d'utilisateur sur les réseaux sociaux
- [ b ] - Recherche inversée de numéro de téléphone
- [ c ] - Générateur d'identité fictive
- [ d ] - Recherche avec Dorks
- [ z ] - Retour

## Auteurs

[Marlottony](https://github.com/Marlottony)

## À propos

Boîte à outils Alex est un outil permettant d'effectuer des scans automatisés sur une cible, comprenant de nombreux outils relatifs au pentest, à l'équipe rouge et à l'équipe bleue.

## Ressources

- **Langage** : Python
- **Dépôt GitHub** : [pentest-toolbox](https://github.com/Marlottony/Toolbox-Alex)

---

Cela devrait répondre à vos besoins et fournir un document clair, professionnel et bien structuré pour votre projet.
