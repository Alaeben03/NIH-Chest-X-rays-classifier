# NIH Chest X-ray Classifier

Ce projet vise à développer un modèle de Deep Learning capable de classifier 14 pathologies thoraciques différentes à partir de la base de données de radiographies du NIH (National Institutes of Health).

## Fonctionnalités
* **Prétraitement** : Analyse exploratoire (EDA), gestion du déséquilibre des classes et préparation des générateurs d'images.
* **Architecture** : Utilisation du Transfer Learning (ex: ResNet, MobileNet ou DenseNet) pour la classification multi-labels.
* **Évaluation** : Suivi des performances via l'AUC-ROC, la précision et le rappel.

## Structure
* `Data_Preprossessing.ipynb` : Nettoyage et préparation des données.
* `Model_creation.ipynb` : Architecture, entraînement et évaluation du modèle.
* `NIH Chest X_Project.docx` : Documentation détaillée de la méthodologie.

## Confidentialité
Les données utilisées pour ce projet appartiennent au laboratoire de recherche et ne peuvent pas être mises en ligne.
