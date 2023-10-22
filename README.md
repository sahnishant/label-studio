# Installation: 

1. Install [python 3.12.0](https://www.python.org/ftp/python/3.12.0/python-3.12.0-amd64.exe)
2. On windows command prompt
```
python -m pip install label-studio
```
3. Now create a folder "Project" and in it 
   - Create the file server.py from github
   - Copy all images given to you
   - This can be done by downloading the git repo as a zip file
4. Open terminal by right clicking inside the folder. You can also open the command prompt. 
   - goto Project folder 
   - type ```python server.py``` and press enter.
```
python server.py
```
5. Open another command prompt or terminal
   - type ```label-studio``` and press enter.
```
label-studio
``` 
   Label studio should open in the browswer. URL ```http://localhost:8080```

6. Create login and password on label studio
   - Create new project. Name it ```Tagging```
   - Press import - upload the JSON file provided
   - GOTO ```SETTINGS->Labelng Interface->Code``` -> copy the Template file  git -> press save. 
7. Goto Project again Click on one of the images. 
8. Now tag each box with the right entity.
9. Once you have processed a batch of 20-30 entities, export in JSON format and Export in JSON-Min format and save the two files in the git repository. 

The first 1-2 images will seem super difficult. But after that it will be super simple
