# Comparaison de modèles pour la correction d'erreurs grammaticales
Ce répertoire contient le code utilisé pour le rapport du projet du cours INF8225.  
Les auteurs sont Alexandre Cojot (2083577), Samy Labassi (1953898) et Malik Saheb (2090957).

## Prérequis
Un compte Google est nécessaire pour exécuter les fichiers `.ipynb`. En fait, ces derniers montent des fichiers se trouvant dans un Google Drive. À cet égard, les fichiers se trouvant dans le dossier `ins` de ce [lien Google Drive](https://drive.google.com/drive/folders/1ZeARmEMr-L--tAaJNbTCahh7dMtqXgnT?usp=sharing) sont sollicités par les fichiers `.ipynb`. Veuillez donc bien les télécharger dans votre disque Drive.  
De plus, l'utilisation de Google Colab est fortement recommandée.  

D'ailleurs, le dossier `outs` contient toutes les sorties générées par le code. Il inclut les fichiers générés pour le jeu de données CoNLL-2014, le modèle BERT et ses outputs, la sortie du modèle BART et les résultats des LLMs testés.

## Utilisation
### Modèle BERT et BART
Les sorties du modèle BERT et du modèle BART sont respectivement générées par les fichiers `BERT.ipynb` et `BART.ipynb`.  
Le fichier `evaluation.ipynb` permet de générer les scores des métriques (F, BLEU et ROUGE) en fonction des sorties de ces deux fichiers.

### LLMs
Le fichier `llms/GEC_LLMs.ipynb` génère les sorties de chaque modèle LLM évalué et calcule les scores de chaque métrique. Les résultats obtenus se trouvent dans le dossier `llms/results` (en plus de se trouver dans le [Google Drive](https://drive.google.com/drive/folders/1ZeARmEMr-L--tAaJNbTCahh7dMtqXgnT?usp=sharing)).
