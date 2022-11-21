# PROJET NLP

Le but de ce projet est d'entrainer un modèle de génération de poèmes.
Nous avons entrainé 2 modèles : Transformers (GPT-2) et RNN (LSTM).

Pour parcourir ce projet, commencer par le notebook ```train_french_model.ipynb```, et la partie de l'entrainement se trouve dans le notebook ```notebook.ipynb```.

1. notebook
---

Pour de raison de performance, nous avons 2 notebooks.
- ```train_french_model.ipynb```: qui contient la partie de l'entrainement. Ce choix a été fait pour ne pas exécuté tout le notebook qui prend beaucoup de temps
- ```notebook.ipynb```: le notebook principal qui contient tout le reste du code.


2. Le dataset
---

- ```data.csv``` contient les données récupérées depuis le site des poèmes (données brutes)
- ```data_new.csv``` contient les données nettoyées, avec les thèmes choisis
- ```dataset_reduc.csv``` contient les données tronquées.

3. Html
---

Le dossier html contient les notebooks en version html, ce qui permet une lecture avec le navigateur sans pouvoir lancer un jupyter notebook.

3. Possibilité 
---
Il est possible si le temps permet de déployer ces modèles via une application web avec Streamlit ou flask par exemple


