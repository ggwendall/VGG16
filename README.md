

![image](https://github.com/ggwendall/ggwendall/assets/48108275/edb15cbf-f45a-472c-b934-44762886a231)

# Projet Transfer Learning pour la Détection de Masques

Ce projet a été développé dans le cadre d'un brief visant à appliquer le Transfer Learning sur une base de données pour identifier si une personne porte un masque ou non. Le projet utilise un apprentissage supervisé et repose sur l'utilisation de la bibliothèque Keras et le modèle VGG16.

## Objectif du Projet

L'objectif principal de ce projet est de développer un modèle de détection de masques en utilisant l'apprentissage supervisé et le Transfer Learning avec le modèle VGG16. Le modèle doit être capable de déterminer si une personne porte un masque ou non à partir d'images capturées soit à partir d'un ensemble de données, soit en temps réel depuis une webcam.

![image](https://github.com/ggwendall/ggwendall/assets/48108275/edb15cbf-f45a-472c-b934-44762886a231)

## Challenges

Ce projet implique plusieurs défis techniques, notamment :

- Manipulation des images : Chargement, redimensionnement et préparation des images pour le modèle VGG16.
- Utilisation de la bibliothèque Keras : Création et configuration d'un modèle Convolutional Neural Network (CNN) avec Keras.
- Transfer Learning : Application du Transfer Learning en utilisant le modèle pré-entraîné VGG16.
- Tests avec la webcam : Développement d'un code Python pour tester le modèle en temps réel à partir de la webcam et afficher un message indiquant si une personne porte un masque ou non.

![image](https://github.com/ggwendall/ggwendall/assets/48108275/edb15cbf-f45a-472c-b934-44762886a231)

## Guide d'Utilisation

### Partie 1 : Base de données, Analyse et Préparation

1. Téléchargez la DataSet à partir du lien suivant : [DataSet](https://drive.google.com/drive/folders/1HOxFk8alSSMshf95ToLEUuYZ1Ki7p90Q?usp=sharing).
2. Chargez les images à partir de la DataSet.
3. Redimensionnez les images pour les adapter au modèle VGG16.
4. Préparez les données pour qu'elles soient compatibles avec le modèle VGG16.
5. Divisez les données en ensembles d'apprentissage, de validation et de test.
6. Visualisez des exemples d'images de la classe "Avec_Masque" et "Sans_Masque".

### Partie 2 : Architecture CNN sur Keras

1. Appliquez la Data Augmentation sur les données d'apprentissage pour augmenter la taille du jeu de données.
2. Chargez et configurez le modèle VGG16 pour l'application de la détection de masques.
3. Utilisez le ModelCheckpoint de Keras pour sauvegarder le meilleur modèle pendant l'apprentissage.
4. Lancez l'apprentissage en utilisant les données d'apprentissage et de validation, enregistrant l'historique de l'apprentissage.
5. Tracez les courbes d'accuracy et d'erreur pour les ensembles d'apprentissage et de validation.
6. Calculez l'accuracy et la matrice de confusion sur l'ensemble de test.

### Partie 3 : Application

1. Testez le modèle développé sur de nouvelles images en affichant le message "Avec masque" ou "Non masque" sur chaque image. Utilisez la fonction `cv2.putText`.
2. Développez un code Python pour activer la webcam et identifier en temps réel si la personne porte un masque ou non, en affichant le message approprié sur l'image capturée.

## Environnement de Développement

- Utilisation de [Google Colab](https://colab.research.google.com/?hl=fr) pour l'apprentissage du modèle.
- Bibliothèques utilisées : Keras, OpenCV, NumPy, Matplotlib, etc.

![image](https://github.com/ggwendall/ggwendall/assets/48108275/edb15cbf-f45a-472c-b934-44762886a231)

## Auteur

Ce projet a été réalisé par Quenet Gwendal.

<div align=center>

<img src="https://media.giphy.com/media/VgCDAzcKvsR6OM0uWg/giphy.gif" width="50"> 

![image](https://github.com/ggwendall/ggwendall/assets/48108275/edb15cbf-f45a-472c-b934-44762886a231)

![Bottom](https://github.com/ggwendall/ggwendall/assets/48108275/1f58de6a-f411-45fd-86a6-e9aa673332e6)
