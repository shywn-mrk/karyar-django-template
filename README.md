# Karyar Django Template

For each pre-commit error you'll lose 0.5 of each exercise score so be careful. Also, each critical error in your design and project structure costs 1 score.
Try not to lose those scores.

## Installation

Make sure you have Python >= 3.9 installed before following these steps.

1 - Clone the project:

```bash
git clone https://github.com/shywn-mrk/karyar-django-template.git
```

2 - Create a virtual environment:

```bash
python -m venv env
```

3 - Activate the virtual environment:

-   Windows:

```bash
env/Scripts/activate
```

-   Mac/Linux:

```bash
source env/bin/activate
```

4 - Install the required packages:

```bash
pip install -r requirements.txt
```

5 - Creating migrations and migrate:

```bash
python manage.py makemigrations

python manage.py migrate
```

6 - Create a super user:

```bash
python manage.py createsuperuser
```

7 - Run the server:

```bash
python manage.py runserver
```
