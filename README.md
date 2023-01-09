# Exemple d'application web en python et API flask/connexion

la structure du projet :

    tree
    .
    ├── READLME.md
    ├── __init__.py
    ├── people.py
    ├── server.py
    ├── static
    │   ├── css
    │   │   └── home.css
    │   └── js
    │       └── home.js
    ├── swagger.yml
    └── templates
        └── home.html


server.py : contient le programme principal.
swagger.yml : contient le descriptif des api
people.py : contient les codes des services qui sont derriere chaque endpoint

les repertoires static et templates contiennent le code du front.

Les pre-requis pour faire fonctionner le projet :
1. Python 3
2. Créer un environnement virtuel Python : dans le directory de l'application : python3 -m venv ./venvApi
3. Lancer l'environnement virtuel : source ./venvApi/bin/activate
4. pip install flask
5. pip install connexion[swagger-UI]
6. Récupérer mes sources sur github : git clone https://github.com/jcbrun/apiPeople .
7. Lancer l'application : python server.py
8. Consulter le site : http://127.0.0.1:5001/
9. consulter la documentation des API : http://127.0.0.1:5001/api/ui


ref : https://realpython.com/flask-connexion-rest-api/
