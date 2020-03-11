# Webapp3

This is a way for people to convert their old webapp2 classes to make them work with python3 using Flask

You can view the source code at https://github.com/ReddingSoftware/Webapp3 The github version is a complete program to demonstrate usage. If you are downloading from github you only need the webapp3.py file.

You can install this module using 

pip3 install webapp3-flask

You also need to list the latest version in your requirements.txt
For Google App Engine you also need to pip install it to your lib file using 

pip3 install -t lib -r requirements.txt

Also, if you pip install you must use:

from webapp3 import *

or

from webapp3 import BaseHandler,webapp2,RequestHandler,webappGet,webappPost

Here is a quick YouTube video demonstrating how to use this module https://youtu.be/P_B1Mu9p0cg
