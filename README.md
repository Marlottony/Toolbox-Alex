Version mise à jour du README incluant les instructions spécifiques pour Debian et Kali Linux :

---

# Boîte à outils Alex

Boîte à outils Alex est un outil permettant d'effectuer des scans automatisés sur une cible, comprenant de nombreux outils relatifs au pentest, à l'équipe rouge et à l'équipe bleue.

### Fonctionnalités principales

- **Reconnaissance** : Whois, recherche de CVE, données DNS, informations sur les certificats HTTP/S.
- **Numérisation** : Scan de ports Nmap, analyse des failles Nikto, découverte d'URL Dirbuster.
- **Exploitation** : Identification et exploitation des failles de sécurité.
- **OSINT** : Recherche de noms d'utilisateur, de numéros de téléphone, générateur d'identités, recherche de dorks.
- **Génération de rapport** : Rapport PDF détaillé des vulnérabilités avec recommandations.
- **Outils divers** : Générateur de shell reverse one-liner.

## Installation

### Prérequis

Assurez-vous d'avoir Python 3.11 installé et configurez un environnement virtuel. Voici les commandes spécifiques pour Debian et Kali Linux :

#### Installation sur Kali et Debian

1. **Mettre à jour la liste des packages et installer `python3.11-venv`** :
   ```sh
   sudo apt update
   sudo apt install -y python3.11-venv
   ```
### Téléchargement du projet

3. **Vous pouvez télécharger la version zip depuis GitHub ou cloner le dépôt via la ligne de commande** :
```sh
git clone https://github.com/Marlottony/Toolbox-Alex
```
Enregistrer le fichier dans Documents.

Après le téléchargement, changez de répertoire et installez les bibliothèques nécessaires pour exécuter le script correctement :

2. **Créer et activer un environnement virtuel** :
   ```sh
   python3.11 -m venv ~/Toolbox-Alex-main/venv
   source ~/Toolbox-Alex-main/venv/bin/activate
   ```

3. **Mettre à jour pip et installer les dépendances** :
   ```sh
   pip install --upgrade pip
   pip install -r ~/Documents/Toolbox-Alex-main/requirements.txt
   ```
### Changement de répertoire et exécution du script

1. **Changez de répertoire** :
   ```sh
   cd ~/Documents/Toolbox-Alex-main/Pentest-toolbox-alex
   ```

2. **Lancez le script avec Python** :
   ```sh
   python pentest-toolbox.py
   ```

### Créer un Alias pour Accéder au Répertoire de N'importe Où

Pour accéder facilement au répertoire `Toolbox-Alex-main` depuis n'importe où, suivez ces étapes :

1. **Ouvrez votre fichier de configuration de shell (`~/.bashrc` ou `~/.zshrc`)** :

   ```sh
   nano ~/.bashrc   # Pour bash
   nano ~/.zshrc    # Pour zsh Fonctionne avec Kali
   ```

2. **Ajoutez l'alias suivant à la fin du fichier** :
   ```sh
   alias pentest-alex='cd ~/Documents/Toolbox-Alex-main && source ~/Toolbox-Alex/venv/bin/activate'
   ```

3. **Sauvegardez et fermez le fichier, puis rechargez la configuration de votre shell** :
   ```sh
   source ~/.bashrc   # Pour bash
   source ~/.zshrc    # Pour zsh
   ```

Maintenant, vous pouvez utiliser la commande `pentest-alex` pour accéder directement au répertoire `Toolbox-Alex` et activer l'environnement virtuel.

### Utilisation

Lancez simplement le script avec Python sans aucun paramètre :

```sh
pentest-alex
python pentest-toolbox.py
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

```
#### [ 1 ] - Reconnaissance

- [ a ] - Requête Whois de base
- [ b ] - Rechercher un CVE
- [ c ] - Obtenir des données DNS sur un domaine
- [ d ] - Obtenir des informations sur un certificat HTTPS
- [ e ] - Extraire toutes les identifications CVE d'une URL spécifique
- [ z ] - Retour
```
```
#### [ 2 ] - Balayage

- [ a ] - Scan de ports Nmap
- [ b ] - Scan Nikto
- [ c ] - Découverte d'URL avec Dirbuster
- [ z ] - Retour
```
```
#### [ 3 ] - Exploitation

- [ a ] - Recherche de vulnérabilités et d'exploits sur un service
- [ z ] - Retour
```
```
#### [ 4 ] - OSINT

- [ a ] - Recherche de noms d'utilisateur sur les réseaux sociaux
- [ b ] - Recherche inversée de numéro de téléphone
- [ c ] - Générateur d'identité fictive
- [ d ] - Recherche avec Dorks
- [ z ] - Retour
```
## Auteurs

[Marlottony](https://github.com/Marlottony)

## À propos

Boîte à outils Alex est un outil permettant d'effectuer des scans automatisés sur une cible, comprenant de nombreux outils relatifs au pentest, à l'équipe rouge et à l'équipe bleue.

## Ressources

- **Langage** : Python
- **Dépôt GitHub** : [pentest-toolbox](https://github.com/Marlottony/Toolbox-Alex)
