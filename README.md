# modern-django-setup
Modern Django Set Up: A Guide on How to Deploy Django-based Web Applications in 2019

Requirements
------------
1.  Python 3+


Installation on Development Machine
-----------------------------------

To run the app on your local machine, you need Python 3+, installed on your computer. If you using pipenv than follow 2nd 1 to 3 steps

1.  Create and activate virtualenv:

        python3 -m venv venv
        . venv/bin/activate

2.  Read requirments file:
      
        pip install -r requirments/local.txt


3.  Create new `.env` file:

        $cp .env.example .env 
        put all keys in .env file

If you using pipenv than

1.  Create and activate pipenv:
        pip3 install pipenv
        pipenv shell

2.  Read requirments file:
        pipenv install -r requirments/local.txt


3.  Create new `.env` file:

        $cp .env.example .env
        