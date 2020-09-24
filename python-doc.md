#Install python 3.8 on ubuntu
https://linuxize.com/post/how-to-install-python-3-8-on-ubuntu-18-04/


#switch to python 3.8
sudo nano .bashrc
alias python='/usr/bin/python3.8'


# Now install virtualenv:
pip install virtualenv

#Setting up Gunicorn systemd file
pip install gunicorn

#Once gunicorn is installed, run command:
gunicorn <your_project_name>.wsgi:application --bind 0.0.0.0:8000
