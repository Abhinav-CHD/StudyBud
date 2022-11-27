# StudyBud
### _A community web app to find people with similar interests and bring them together_

## Preview
Live - [Link](https://studybud-production.up.railway.app/)
 <br/>
Backup (may take a while to load) - [Link](https://studybud-u3jj.onrender.com/)

## Features

- Create/Delete a new Topic
- Add/Delete comments to Exitsing topic
- Update user profile
- View profile of a particular user
- Search for a particular room

## Tech

StudyBud need following tech stack to work properly:

- [Django] - Backend language
- [SQLite] - DataBase
- [HTML] - Giving structure to our website
- [CSS] - Styling the webpages
- [JavaScript] - Adding functionality to our website


## Installation

Dillinger requires [Node.js](https://nodejs.org/) v10+ to run.

It is recommmend that you create a virtual env.

```sh
cd StudyBud
python -m venv env
env\Scripts\activate
```

Install the dependencies

```sh
pip install -r requirements.txt
```
## Run
Run the development server using the following command

```sh
python manage.py runserver
```

Verify the deployment by navigating to your server address in
your preferred browser.

```sh
127.0.0.1:8000
```

[//]: # (These are reference links used in the body of this note and get stripped out when the markdown processor does its job. There is no need to format nicely because it shouldn't be seen. Thanks SO - http://stackoverflow.com/questions/4823468/store-comments-in-markdown-syntax)

   [Django]: <https://www.djangoproject.com/>
   [SQLite]: <https://www.sqlite.org/index.html>
   [CSS]: <https://developer.mozilla.org/en-US/docs/Web/CSS>
   [HTML]: <https://developer.mozilla.org/en-US/docs/Web/HTML>
   [JavaScript]: <https://developer.mozilla.org/en-US/docs/Web/JavaScript>
