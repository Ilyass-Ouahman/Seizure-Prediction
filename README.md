# Support Vector Machines for Real-Time Seizure Prediction using Neural Data.
---

- Les fichiers sources pertinents sont disponibles dans le [dossier d'évaluation].
- The main paper can be found in file : ENSAM-Rabat-UM5-Mémoire Master Electrical Engineering.docx


## Usage et executions. 

1. Téléchargez la base de données CHB-MIT depuis [https://physionet.org/content/chbmit/1.0.0/](https://physionet.org/content/chbmit/1.0.0/) en utilisant la commande suivante :
`wget -r -N -c -np https://physionet.org/files/chbmit/1.0.0/`

2. Connectez `data_gen_train_test.py` avec `train_test_data.xlsx`. Le fichier Excel a déjà été rempli avec les informations pertinentes.

3. Décommentez la commande appropriée dans analyst.sh et enregistrez le fichier. Ensuite, exécutez-le depuis le terminal. Vous devrez peut-être attribuer les permissions d’exécution à ce script en utilisant la commande : `chmod +x analyst.sh`


4. Le programme `analyst.py` contient les algorithmes principaux. Il comporte deux méthodes principales : `teach` et `think`. Vous devriez consulter les commandes d'exemple dans `analyst.sh` pour comprendre comment invoquer ces méthodes.


Ilyass Ouahman - Département Génie Électrique - ENSAM Rabat- Université Mohammed V 
