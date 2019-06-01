# Conference-Management-System
A python django project for conference management. There are chairs who can create new conferences, accept or reject submitted abstracts and papers and chairs can assign abstracts and papers to reviewers for them to review.
There are authors who can upload abstracts and papers and submit them to conferences. They get feedback from reviewers and update their papers accordingly.
There are reviewers whose duty should be obvious by now. 

Conferences have abstract submission deadline, paper submission deadline, review deadline, start date and end date. For example authors can't submit abstracts to conferences if abstract submissino deadline has passed.

All information about acceptance of papers or review assignments etc. are mailed to people who are concerned about that information.

All 3 type users have to sign up to the system. Chairs and reviewers need to be confirmed by system admin. Admin login is email:admin, password:admin.


# Running the project
If you wanna run the project create a python 3 virtual environment and then you can install the dependencies using "pip install reqiurements.txt" command inside the main folder. Then run "python manage.py runserver" command to run the app. You can use the app from localhost:8000.


