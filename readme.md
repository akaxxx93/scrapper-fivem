# FiveM User Scrapper

Ce script est conçu pour récupérer des informations sur les utilisateurs de FiveM à partir du cfx.

## Fonctionnalités

- **Scraping des utilisateurs**: Le script extrait les informations des serveurs FiveM à partir de sources en ligne.
- **Stockage des données**: Les données récupérées sont stockées dans un fiché texte pour une utilisation ultérieure.

## Installation

1. Clonez ce dépôt sur votre machine locale:

    ```bash
    git clone https://github.com/InsurWeb/FiveM-Scrapper.git
    ```

2. Assurez-vous d'avoir Python 3 installé sur votre système.

3. Installez les dépendances requises en exécutant la commande suivante ou ouvrir setup.bat:

    ```bash
    pip install -r requirements.txt
    ```

## Utilisation

1. Exécutez le script principal `Start bump.bat Ou main.py`:

    ```bash
    python scrapper_by_aka.py
    ```

2. Suivez les instructions pour démarrer le scraping et le stockage des données.

## Configuration

- **URL de la source de données**: Définissez le cfx du serveurs à partir de laquelle vous souhaitez extraire les données des utilisateurs de FiveM dans serveur.txt Exemple : cfx.re/join/6vm8z8 se transforme en : 6vm8z8

## Contribution

Les contributions sont les bienvenues! Si vous souhaitez améliorer ce projet, n'hésitez pas à créer une pull request.

## Licence

Ce projet est sous licence [MIT](LICENSE).
