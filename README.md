


# How to run this project Locally:

1-You need to install the latest version of python and Django.

2-make sure you are in the plantsforu directory either from zip file or git clone https://github.com/nawafak74/my-first-blog.git

3-Start the virtual machine by running:

source myvenv/bin/activate

4- In a python virtual environment, run into the command line:

pip install -r requirements.txt
python manage.py migrate blog
python manage.py createsuperuser (to create an admin user)

5- To run the server Run in the command line:

python manage.py runserver

6- Go to http://127.0.0.1:8000/ or http://127.0.0.1:8000/drafts or http://127.0.0.1:8000/login http://127.0.0.1:8000/admin 

Using docker, Please make sure that Docker is installed. Then run:
docker-compose up

The application will be live at [0.0.0.0:8000](0.0.0.0:8000)

please find the deployed app on plantsforu.pythonanwyhere.com or nawafak74.pythonanywhere.com
please log in to the system to access features using 
username: plantsforu 
password: csc3131bs


