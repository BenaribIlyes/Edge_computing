# Edge_computing


# 💻 Projet Edge Computing : Reconnaissance Vocale (Kaggle)

Ce dépôt contient le code et les fichiers de configuration associés au projet de reconnaissance vocale basé sur le "TensorFlow Speech Recognition Challenge".

---

## 📥 Téléchargement des Données (DATA)

**ATTENTION :** Les données d'entraînement et de test originales sont trop volumineuses pour être stockées directement sur GitHub, même avec Git LFS.

Pour exécuter le code de ce projet, vous devez **télécharger les ensembles de données complets directement depuis Kaggle**.

### 1. Source des Données

| Fichier | Taille approximative | Description |
| :--- | :--- | :--- |
| `train.7z` | 1.1 Go | Jeu de données d'entraînement (fichiers audio) |
| `test.7z` | 2.6 Go | Jeu de données de test (fichiers audio) |
| `sample_submission.7z` | 512 Ko | Fichier d'exemple de soumission |

**Lien vers le Challenge Kaggle :**
[TensorFlow Speech Recognition Challenge - Data](https://www.kaggle.com/competitions/tensorflow-speech-recognition-challenge/data)

### 2. Étapes de Configuration

Après avoir téléchargé les fichiers depuis Kaggle :

1.  Placez les trois archives (`train.7z`, `test.7z`, `sample_submission.7z`) dans le répertoire `data/compressed_data/` de ce dépôt.
2.  Décompressez le contenu de `train.7z` dans le dossier `data/uncompressed_data/train/`.
3.  Décompressez le contenu de `test.7z` dans le dossier `data/uncompressed_data/test/`.
4.  Vous êtes maintenant prêt à exécuter les notebooks de *preprocessing* et d'entraînement.
