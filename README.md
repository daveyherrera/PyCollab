# PyCollab
Python Blackoboard Collaborate script to download recording based on Blackboard Learn courses linked to Blackboard Collaborate session.
and get:
-	Recording Report in a CSV file (Recording_ID, Storage Size, Duration, Creation Date, Duration)
-	Downloads local folder that will receive the MP4 video recording files
-	Command line attributes: 1) to load external file that list courses_id   2)  weeks int value to search for recording  behind current date.


License: <a href="https://github.com/zerausolrac/PyCollab/blob/master/LICENSE"> MIT License</a>


## 1 Instalation
You need to have installed Python 3.7+ 

## 2 Install requirements 
```
pip3 install -r requerimientos.txt
```

## 3 Add Blackbord Collaborate and Learn Credentials
```
edit content of Config.py file
```


## 4 Modify list of courses ID
```
edit cursos.txt file or edit uuid.txt file
```


## 5 Run the script

```
### Search for Learn recording 
python3 Collab.py -f cursos.txt -w 12

### External UUID of Collab Session
python3 Collab.py -e uuid.txt -w 12

```
- where -f is pointing to file named in this case: "cursos.txt" having within listed  of all Blackboard course ID by row
- where -e pointoing to file  named in this case: "uuid.tt" having within listed of external UUID (session)
- where -w is a value of weeks back for as starting point of searching for recordings

# Video
English:
https://www.youtube.com/watch?v=UxKZvBw_-NU


Español
https://www.youtube.com/watch?v=0ov-HZJeAE0&feature=youtu.be

