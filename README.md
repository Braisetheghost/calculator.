# calculator

## Run calculator

### Sum

Example : 
```bash
python src/main.py -op sum -val1 1 -val2 2
```

Exercice 1 :

1) git init
   git clone https://github.com/vjobanda/calculator.git calculator_base

2) Site : https://github.com/new -> nommez le dépôt calculator

3) git clone https://github.com/Braisetheghost/calculator. ./calculator

4) Copier contenu de calculator_base précédemment récupéré dans calculator

5) git status -> vérifier si le dépôt local a été modifié

6) git 
a) git add src/ -> ajoute un ou des fichier(s) à la liste des fichiers à déposer
b) git commit -m "message de commit" -> saisir le message affiché pour ce dépôt
c) key (expire le 01/04/2025)
d) git push origin


Exercice 2 :

git fetch -> vérifier si le dépôt distant a été modifié
1) git pull -> récupérer les modifications du dépôt distant

2) 
a) python -m venv venv
b) .\venv\Scripts\activate
c) pip install coverage
d) pip freeze > requirements.txt
e) python -m coverage run -m unittest tests/test_calculator.py
   coverage report -m
f) Créer fichier .gitignore -> ouvrir et taper *.coverage, venv
g) git add *
   git commit -m "ajout requirements.txt et .gitignore"
   git push origin
