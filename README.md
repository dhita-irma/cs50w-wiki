# Wiki - Simple Encyclopedia
Simple online encyclopedia similar to Wikipedia built with Django. 

## Table of Contents
- [Project Summary](#project-summary)
- [Technologies](#technologies)
- [Features](#features)
- [Setup](#setup)


## Project Summary
This project is created for [Project 1 of CS50W](https://cs50.harvard.edu/web/2020/projects/1/wiki). Wiki consists of a number of encyclopedia pages that user can visit by clicking the link on the homepage or directly typing the URL. User can also search entry on the search box, create entry, and also editing the existing entry. 

## Technologies 
This project is created with Python Django 3.1

Library: 
- django-crispy-forms v1.9.2 is used to style forms in Django
- markdown2 v2.3.9 is used to convert Markdown to HTML 

## Features 
- **Entry page**: Visiting /wiki/TITLE, where TITLE is the title of an encyclopedia entry, should render a page that displays the contents of that encyclopedia entry. If URL does not exist, an error page will be shown, inditating that the requested page was not found. 
- **Index Page**: User can click on any entry name on the homepage to be taken directly to that entry page.
- **Search**: Allow the user to type a query into the search box in the sidebar to search for an encyclopedia entry.
- **Create Entry**: Clicking “Create New Page” in the sidebar would take the user to a page where they can create a new encyclopedia entry. User can enter Markdown content in the textarea.
- **Edit Page**: On each entry page, the user should be able to click a link to be taken to a page where the user can edit that entry’s Markdown content in a textarea.
- **Random Page**: Clicking “Random Page” in the sidebar would take user to a random encyclopedia entry.
- **Markdown to HTML Conversion**: On each entry’s page, any Markdown content in the entry file would be converted to HTML before being displayed to the user using markdown2 library. 

## Setup 
- This project requires Python 3 installed on your computer. 

- Clone or download this repository in the folder and open it in your editor of choice.
- Create and activate [virtual environment](https://docs.python.org/3.9/library/venv.html) by running following command in the terminal of the base directory of this project:


    ```
    python -m venv <virtual environment name>
    C:\> <venv address>\Scripts\activate
    ```

- Then install the project dependencies with
    ```
    pip install -r requirements.txt
    ```
- Now you can run the project with this command
    ```
    python manage.py runserver

    ```

