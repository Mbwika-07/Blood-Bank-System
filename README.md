# Blood Bank Management System
--
This is a simple blood bank management system that allows users to log in as either patient (able to request blood from admin), donor (able to donate blood) or admin (controls aspects of the system such as approving donated blood or approving a patients request for blood).

This system is built using HTML CSS (frontend), django (backend) and sqlite3 (database)
### Homepage
![homepage snap](https://github.com/Mbwika-07/Blood-Bank-System/blob/main/static/screenshot/home.png?raw=true)


### Admin
Create Admin account using following command
```
python3 manage.py createsuperuser
```

---

## HOW TO RUN THIS PROJECT
Download This Project Zip Folder and Extract it
Move to project folder in Terminal. Then run following Commands :

```
python3 -m pip install -r requirements.txt
```

```
python3 manage.py makemigrations
python3 manage.py migrate
python3 manage.py runserver
```
Now enter following URL in Your Pc Browser
```
http://127.0.0.1:8000/

