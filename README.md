# django-importcsv-scorecsv-exportcsv
Django code that imports CSV, scores the CSV and exports the data with the scores
As it's a djngo program, there are lots of folders, which I have put in a zip file with the CSV files

download this file then

Instructions
This based on user having some basic Django experience
Import all of the files
1)	Create the SVM model to be pickled (code used	predictin model.py)
2)	In the commands line (where manage.py is stored)
•	Python manage.py migrate
•	Python manage.py createsuperuser
•	Python manage.py makemigrations
•	python manage.py migrate --run-syncdb
•	Python manage.py runserver

3)	Goto the Django page (web browser)
 
4)	Click ‘>>Import Data’

 
5)	Import applicants.csv
6)	Return to home page
7)	Click on Update data
 
8)	Click on Return to Homepage
9)	Click on Export data

 
Click Export and you will receive your CSV file with the population scored
If you want to delete all of the data afterwards, return to Homepage and use the delete data page.



