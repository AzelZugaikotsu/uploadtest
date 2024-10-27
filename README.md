Steps in setting up the app on codespaces

Create a new repository on GitHub and add all the files (app.py, templates/login.html, static/styles.css, static/script.js).

Include a .gitignore file that excludes *.db files and other sensitive data (like a .env file if you use environment variables).

In your repo, click on the Code button, and select Codespaces > New codespace.
This will open a cloud-based VS Code environment where you can install dependencies and run the Flask app.

The requirements are already present in the file called requirement.txt

So use pip install -r requirements.txt

python app.py
