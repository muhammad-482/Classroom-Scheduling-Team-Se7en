# Classroom Scheduling web application

Classroom Scheduling is web application for genarting a unversity time tabele system used by college register to automate the procsses of of genrating time table for all courses and thier teachers and classroom.
# Problem Solved:
Generate lectures tables for every classroom and assign it to an availabe room 


# How to use it 

We used the [genetic algorithm](https://www.geeksforgeeks.org/genetic-algorithms/) for generating the optimal timetable that suites the teachers and classroom capacity.

## First Installation & Run

First, use the package manager [pip](https://pip.pypa.io/en/stable/) to install Django.\
_Syntax in the same order_ 
>pip install django # Install Django Packages

>django-admin startproject project_name # Create a Project
>cd [project_name]

>python manage.py makemigrations # Create new migrations

>python manage.py migrate # Apply Migrations

>python manage.py createsuperuser # Create User for admin

>python manage.py runserver

## Admin username and password
username: mohammed

password : 12345


## Second, you enter the information of Six objects:
- *Room*: which is classrooms and their capacity.
- *Instructor*: which is the teacher info (ID & name).
- *Meeting Time*: which is the time that the classroom will be busy for meeting, so it will not be included in the timetable generation at the time of the meeting
- *Course*: which include information about the course like course ID, name, max number of students and instructor name
- *Department*: which include information about department ID, name and department's courses 
- *Section*: which is the batch info and to what department it belongs

### Finally press the generate button, then WAIT for the algorithm to do its magic (more complex the input, more time it takes).





## acknowledgment
- this project was built using [django](https://www.djangoproject.com/).
- Genetic algorithm.

#### <<Please make sure to update tests as appropriate.>>
