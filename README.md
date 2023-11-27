# YourMoneyTrackerMail


## Installation
Note: This project was developed with Python 3.10 (pip 22) in Linux Mint 20.

Create a virtual environment
```bash
python3 -m venv env
```
Activate the virtual environment
```bash
source env/bin/activate
```
Or in Windows (PowerShell)
```bash
\env\Scripts\Activate.ps1
```
Install the requirements
```bash
pip install -r requirements.txt
```
Create migrations
```bash
python manage.py makemigrations
```
Run the migrations
```bash
python manage.py migrate
```
Create a superuser
```bash
python manage.py createsuperuser
```
Run the server
```bash
python manage.py runserver
```

## Stack
+ Python 3.10
+ Django 4.2
+ SQLITE - Dev
+ PostgreSQL - Prod
+ HTML - CSS
+ JavaScript Vanila
+ GitHub Action (CI/CD)
+ VPS Ubuntu in DO

### Collaborators
- [Lorenzo]
- [Gael]
