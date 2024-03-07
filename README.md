# Reconnaissance-d-Actions-dans-la-VideoReconnaissance d'actions humaines dans les vidéos

# Downloads the UCF-101 dataset:http://crcv.ucf.edu/data/UCF101/UCF101.rar
# https://www.crcv.ucf.edu/data/UCF101/UCF101TrainTestSplits-RecognitionTask.zip


Ce projet vise à développer un système de reconnaissance  de similarite d'actions dans les vidéos en utilisant des réseaux de neurones convolutifs avec des couches LSTM et des mécanismes d'attention. Les scripts fournis permettent de former un modèle sur le jeu de données UCF-101 et d'évaluer ses performances.

Contenu du projet
models.py : Définition des modèles de réseau neuronal, y compris ConvLSTM, Encoder, LSTM, Attention, et ConvClassifier.
jeu de donnees .py : Implémentation de la classe Dataset pour le chargement des données du jeu de données UCF-101.
extraction.py : Fonction pour extraire les images à partir des vidéos.
entrainement.py : Script pour l'entraînement du modèle.
verification.py : Script pour tester le modèle sur l'ensemble de test.


Préparation des données :

Téléchargez le jeu de données UCF-101 et extrayez-le dans le répertoire spécifié.
Utilisez le script extraction.py pour extraire les images des vidéos.
Entraînement du modèle :

Utilisez le script entrainement.py pour entraîner le modèle. Vous pouvez spécifier différents paramètres tels que le chemin du jeu de données, le nombre d'époques, la taille du batch, etc.
Test du modèle :

Après l'entraînement, utilisez le script verification.py pour tester le modèle sur l'ensemble de test.
Démonstration de la détection de chute :

Utilisez le script demo.py pour effectuer une démonstration de la détection de chute en spécifiant le chemin de la vidéo à tester.
Remarques supplémentaires
Les scripts peuvent être personnalisés en fonction de vos besoins, par exemple en ajustant les hyperparamètres du modèle ou en modifiant les chemins des fichiers.
Pour obtenir de meilleurs résultats, vous pouvez expérimenter avec différents modèles, techniques de prétraitement des données, etc....
