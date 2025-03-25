### Exploration des Données des Universités Américaines
## Description du Projet
Ce projet consiste à explorer et analyser les données des universités américaines afin d'identifier les critères influençant le choix des étudiants. L'objectif principal est d'analyser des facteurs comme le nombre de candidatures reçues, les types d'universités, et de visualiser les tendances à travers des graphiques. Le projet met en œuvre des techniques de data cleaning et de visualisation de données en utilisant Python.

## Objectifs
Extraction des données : Extraire les données à partir d'un fichier Excel.

Nettoyage des données : Appliquer des techniques de data cleaning avec Pandas pour préparer les données.

Transformation des données : Utiliser Pandas pour transformer les données en informations exploitables.

Visualisation des données : Créer des graphiques interactifs pour représenter les tendances, notamment les moyennes de candidatures en fonction du type d'université et le classement des universités par nombre de candidatures.

Stack Technique
Python : Langage principal utilisé pour le nettoyage, la transformation des données et la visualisation.

Pandas : Librairie principale pour la manipulation et le nettoyage des données.

NumPy : Utilisé pour les calculs numériques et statistiques.

Matplotlib : Librairie de base pour la création de graphiques.

Seaborn : Librairie de visualisation pour créer des graphiques avancés avec une meilleure présentation.

## Étapes du Projet
1. Extraction des Données
Les données ont été extraites à partir d'un fichier Excel contenant des informations sur les universités américaines, telles que :

Le nombre d'étudiants inscrits.

Le nombre de candidatures reçues.

Les différents types d'universités (publiques, privées).

2. Nettoyage des Données
Les données brutes ont été nettoyées pour éliminer les doublons, gérer les valeurs manquantes et corriger les erreurs de formatage.

Pandas a été utilisé pour effectuer ce nettoyage et transformer les colonnes pour les rendre prêtes à l’analyse.

3. Transformation des Données
Les données ont été transformées en informations utiles pour les visualisations :

Calcul des moyennes de candidatures par type d'université.

Identification des Top 20 des universités ayant reçu le plus grand nombre de candidatures.

4. Visualisation des Données
Des graphiques ont été créés pour explorer les tendances suivantes :

Moyennes de candidatures : Histogramme représentant les candidatures selon le type d'université.

Top 20 des universités : Un autre histogramme affichant les 20 universités ayant reçu le plus de candidatures.

5. Interprétation des Résultats
Les graphiques permettent de tirer des conclusions sur les critères qui influencent le plus le choix des universités par les étudiants. Par exemple :

Quel type d'université reçoit le plus de candidatures ?

Quelles sont les universités les plus populaires ?

## Structure du Projet
bash
Copier
Modifier
├── Data/                   # Dossier contenant les fichiers de données (fichier Excel)
├── Scripts/                # Contient le code Python pour nettoyage et visualisation
│   ├── data_cleaning.py    # Script pour nettoyer les données avec Pandas
│   └── data_visualization.py  # Script pour créer les graphiques
├── README.md              # Documentation principale du projet
 
## Instructions d'Installation
Prérequis
Avant d'exécuter ce projet, assurez-vous d'avoir les bibliothèques suivantes installées :

Pandas : pip install pandas

NumPy : pip install numpy

Matplotlib : pip install matplotlib

Seaborn : pip install seaborn

Étapes pour utiliser le projet
Clonez ce dépôt :

sh
Copier
Modifier
git clone https://github.com/JennyTchiegue/Analyse_Universites.git
Accédez au répertoire du projet :

sh
Copier
Modifier
cd Analyse_Universites
Exécutez le script de nettoyage des données :

sh
Copier
Modifier
python Scripts/data_cleaning.py
Exécutez le script de visualisation des données :

sh
Copier
Modifier
python Scripts/data_visualization.py
Vous verrez les graphiques générés s'afficher à l'écran.

Contributions
Si tu souhaites contribuer à ce projet, voici les étapes à suivre :

Fork ce dépôt.

Crée une nouvelle branche pour ta fonctionnalité (git checkout -b feature-xyz).

Commits tes changements (git commit -m "Ajout de la fonctionnalité XYZ").

Pousse ta branche (git push origin feature-xyz).

Crée une Pull Request.

## 📩 Contact
Si tu as des questions, n'hésite pas à me contacter sur [LinkedIn](https://linkedin.com/in/jenny-tchiegue-907803257) ou à ouvrir une issue sur GitHub ! 🚀


