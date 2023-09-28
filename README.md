# Clone de ChatGPT avec Flask et JavaScript
Ce projet est un clone de ChatGPT utilisant Flask et JavaScript

## 🛠️ Technologies
- Backend: Python 3.10, Flask
- Frontend: JavaScript, Jinja2, TailwindCSS (Standalone CLI - https://tailwindcss.com/blog/standalone-cli)
- Gestion des dépendances: Poetry (https://python-poetry.org/)

## 🚀 Installation & Utilisation
- Clonez le repo et naviguez dans le dossier :
```git clone https://github.com/Cecile-Hirschauer/FlaskGPT.git```

- Installez les dépendances avec Poetry :
``poetry install
``

- Définissez la clé API OpenAI :
``echo "OPENAI_API_KEY=<votre_clé_api>" > .env``

- Démarrez l'application :```poetry run python app.py```

- Ouvrez http://127.0.0.1:5000/ dans votre navigateur.