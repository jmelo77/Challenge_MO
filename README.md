# CHALLENGE MO TECNOLOGIES

## Introduction

+ [Python 3.7.6](https://www.python.org/downloads/release/python-376/).
+ The framework was used [Django](https://pypi.org/project/Django/).
+ For the unit tests the library was used [Unittest Django Rest Framework] and the Postman app.    

## Prerequisites

+ Install [Python 3.7.6](https://www.python.org/downloads/release/python-376/)

Enable virtual environment
Python and then install the project dependencies.

```commandline
Install:
python -m venv venv
.\venv\Scripts\activate
python -m pip install -r requirements.txt
python manage.py makemigrations pokemon_api
python manage.py migrate

Test:
python manage.py test

Command Line Application:
python manage.py fetchpokemondata -h  # runs built-in help
python manage.py fetchpokemondata 1  # fetch and store evolution-chain(pokeapi) with id 1
python manage.py fetchpokemondata 1 2 3  # fetch and store evolution-chains with ids 1,2,3...

Run server:
python manage.py runserver

Web Service:
http://127.0.0.1:8000/api/v1/pokemon/ # List of available pokemons
http://127.0.0.1:8000/api/v1/pokemon/{name_pokemon} # JSON pokemon features, example: http://127.0.0.1:8000/api/v1/pokemon/bulbasaur

```

## Entity Relationship Diagram Pokemon API - MO Tecnologies. 

![alt text](https://github.com/jmelo77/Challenge_MO/blob/main/Entity_Relationship_Diagram.png)