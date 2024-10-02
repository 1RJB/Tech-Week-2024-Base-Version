# Tech Week 2024 Base Version - Web Application
Slides link: https://docs.google.com/presentation/d/1YcWyoGd5nbPc7CjwYfzuHfpE24dzsBE0sF-fc27WybE/edit?usp=sharing 

## Information
Packages used:
1. Flask ( Web framework in Python ) 
2. Flask-PyMongo ( Extension to simplifies using MongoDB ) 
3. Pymongo
  - Core library for interacting with MongoDB databases
  - Execute queries,insert/update/delete documents
  - Handle more complex MongoDB operations

    
## Steps to setup
  - Ensure Python and selected code interpreter installed, in this case VSCode
  - Install MongoDB
  - Create a virtual environment using "python -m venv myenv" and connect to the venv Python interpreter
  - Install the below packages using "pip install -r requirements.txt", or manually install each:
    - Install flask
    - Install flask-pymongo
  - Create connection and connect MongoDB database through VSCode's extension (or other method of connection, e.g. MongoDBCompass)
  - Run "python app.py"
