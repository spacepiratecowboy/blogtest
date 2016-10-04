README - Hack-A-Thing Interlude

Who: Elizabeth Brissie, Jasper Bingham, Audyn Curless
What: For our “Hack-A-Thing” project, we wanted to build a simplistic blog website that would allow for an admin to post onto a live web page using the Django framework.
Why: For our CS98 project (Agora - the Campus Craigslist), we wanted to try out some of the technologies involved in web development. Specifically, we wanted to experiment with blog creation (the autonomous action being a “posting” similar to that of a listing), and then attempt the nitty-gritty of running a server, Django models, admin accounts, HTML, CSS and template extending. 
How: By following along with the Django Girls tutorial for web development (https://tutorial.djangogirls.org/en/), we used the Django framework complete with a virtual environment, Python and python-anywhere in order to run our server. Each of the members of our team completed the tutorial individually and then chose one to submit as we discussed and compared what we learned 
What we learned: We learned how mallable Python is in terms of creating a suitable backend. Also, we learned the typcical work flow for web development (i.e making changes locally, pushing changes to GitHub, and then pulling changes down onto a live server). We played aorund with Models, Views and Controllers as well as discussed how we would like to host our webpage and what frameworks we would consider using (aside from Django). 

How to set up the project:
* Install python, pip and virtualenv
* Inside root of directory, run `virtualenv venv`
* Run `source venv/bin/activate`
* Run `pip install -r requirements.txt`
* Run `python manage.py createsuperuser` and follow the prompts to create a local admin account
* Run `python manage.py runserver` and then navigate to `localhost:8000/admin` in a web browser
* Log into the admin page, then use the UI to create a new post, or several posts
* Navigate to `localhost:8000` and you will see your posts displayed in a small feed