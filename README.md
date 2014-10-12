# NeoClient MovieDB Example

![Imgur](http://i.imgur.com/VECZ25P.png)

[![Deploy](https://www.herokucdn.com/deploy/button.png)](https://heroku.com/deploy) | 1 dyno + 1 GrapheneDB chalk addon (all-free)

[Live App Here](http://guarded-reef-9268.herokuapp.com/)

Simple Silex App using [NeoClient](https://github.com/neoxygen/neo4j-neoclient).

## Usage 

### Clone the repository

```bash
git clone https://github.com/ikwattro/neo4j-neoclient-example
```

### Install the dependencies

```bash
cd neo4j-neoclient-example
composer install --no-dev --optimize-autoloader
```

### Run the app and import the fixtures

```bash
php -S localhost:8000
```

Navigate to http://localhost:8000/import

### Enjoy !


---

Author : Christophe Willemsen ([@ikwattro](https://twitter.com/ikwattro))