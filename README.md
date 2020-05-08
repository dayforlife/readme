# challenge_project

this is a simple setup our app

# Quick start

1. Download our app from this repo, open terminal and past this command in terminal
```
git clone git@github.com:ylankgz/challenge_backend.git
```

2. Create virtual envoirement, past this command in terminal in derictory challenge_backend
```
python3 -m venv venv
```

3. Activate your venv in terminal 
```
source venv/bin/activate
```

4. You should see at left side terminal (venv)
```
(venv) hello@hello-TM1801:~/Desktop/challenge_backend$
```

5. Install all requirements
```
pip install -r requirements.txt
```

6. Open project in VSCODE

7. In main folder create ".env" file and we send you keys via telegram
```
touch .env
```
8. Make migration step by step
```
python manage.py makemigrations accounts
```
```
python manage.py makemigrations challenges
```
```
python manage.py migrate
```  

9. Start project in localhost
```
python manage.py runserver
```