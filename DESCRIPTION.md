#Steps
- To install virtual env
   * sudo apt install python3.10-venv
- Create and run the virtual env
   * python3 -m venv venv
   * . venv/bin/activate
- To check missing modules  
   * python3 manage.py runserver
- To install django
   * pip3 install django
- Creating a requirements.txt file to capture dependancies
    * pip3 freeze > requirements.txt
- Running the server 
    * python3 manage.py runserver
 - Build image
    * sudo docker build -t breakout2 .


