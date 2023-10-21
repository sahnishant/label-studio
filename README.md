# Installation: 

1. Install [python 3.12.0](https://www.python.org/ftp/python/3.12.0/python-3.12.0-amd64.exe)
2. On windows command prompt
```
python -m pip install label-studio
```
3. Now create a folder "Project" and in it 
   - Create the file server.py from github
   - Copy all images given to you 
4. Open command prompt,
   - goto Project folder 
   - type ```python server.py``` and press enter.
```
python server.py
```
5. Open another command prompt 
   - type ```run label-studio``` and press enter.
```
run label-studio
``` 
   Label studio should open in the browswer. URL - ```http://localhost:8080```
6. Create login and password on label studio and Login.
   - Create new project and name it ```Tagging```
   - Press import(blue button) and upload the JSON file given to you
   - GOTO ```SETTINGS->Labelng Interface->Code``` and copy the Template file in the git there and press save. 
7. Click on one image or the <> tag. 
8. Now tag each box with the right entity.


The first 1-2 images will seem super difficult. But after that it will be super simple
