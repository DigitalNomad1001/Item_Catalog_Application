# Backend: Item Catalog Application Project
## Udacity: Full Stack Web Development Nanodegree

**Licensing:** 
Anyone is free to use this code as you please. 

**Contributing:**
Anyone is free to contribute.

**Project:** 

 An application that integrates third party user registration and authentication. The application provides a list of items within a variety of categories. Authenticated users have the ability to post, edit and delete their own items. 

**Install:**               **Installation commands:**

* python                   * sudo apt install python-pip
* sqlalchemy               * $ pip install sqlalchemy
* Flask                    * $ sudo pip install Flask
* oah2client               * $ sudo pip install --upgrade oah2client


**Instructions:**
* Be sure to set up your local environment. Use port 8000 or any others that are not in use yet. 
* Install Vagrant and VirtualBox
* Clone the fullstack-nanodegree-vm [ https://github.com/udacity/fullstack-nanodegree-vm ]
* Launch the Vagrant VM (vagrant up)
* Write your Flask application locally in the vagrant/catalog directory (which will automatically be synced to /vagrant/catalog within the VM).
* Run your application within the VM (python /vagrant/catalog/application.py) 

* Clone this repository
* Sample crypto database: python examplecatalog.py.
* Run the program: python application.py.
* Access and test your application by visiting http://localhost:8000



**Different views were deveolped according to the provided guide:**git 

```
Homepage displays all current categories along with the latest added items.
Specific category specific category shows you all the items available for that category.
Specific item shows you specific information of that item.
Google Accounts Loggin. Page implements a third-party authentication & authorization service instead of implementing its own, insecure authentication & authorization spec.
API Endpoints. The project implements a JSON endpoint that serves the same information as displayed in the HTML endpoints for an arbitrary item in the catalog.
CRUD: Read. Website reads category and item information from a database.
CRUD: Create. Website includes a form allowing users to add new items and correctly processes submitted forms.
CRUD: Update. Website does include a form to edit/update a current record in the database table and correctly processes submitted forms.
CRUD: Delete. Website does include a function to delete a current record.
```