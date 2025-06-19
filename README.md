# Adroit-Scheduler
----------------------------------------------------------------------------------------------------------------------------
### An intelligent timetable generator that generates University timetable using `Genetic Algorithm`.

 #### Dependencies:
 1. python3.6 or above
 2. Django2.0 or above
 
#### Run on your local machine by:
* `cd M1`
* `python manage.py runserver`
* then go to port `http://127.0.0.1:8000/timetable_generation/` to run the local server

#### About the project:
This project uses genetic algorithm to satisfy the constraints related to Timetable scheduling. The program satisfies the following constraints:- 

| Hard Constraints                                  | Soft Constraints                                     |
| --------------------------------------------------|:----------------------------------------------------:|
| Unique class timing                               | classes are alloted according to section requirements|
| Course.students <= room.seating capacity          | All courses are according to their department        |
| Two classes dont have same room                   | Even distribution of course in a section per week    |
| Class timing for each teacher is unique           |
| Teachers are allocated to their course accordingly|

#### Features:
- Automatic generation of optimal timetables based on multiple constraints
- Management of instructors, courses, rooms, and meeting times
- User-friendly interface for inputting timetable requirements
- Genetic algorithm implementation for optimization

#### Developer:
Created by Adroit Developer team &copy; 2023
