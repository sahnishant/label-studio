# Installation: 

1. Install [python 3.12.0](https://www.python.org/ftp/python/3.12.0/python-3.12.0-amd64.exe)
2. On windows command prompt
   
   <img src="https://github.com/sahnishant/label-studio/assets/134548275/cd561870-e972-4720-a6a3-bdefcd2f192f" alt="image" width="30%" height="30%">

```
python -m pip install label-studio
```
3. Now create a folder "Project" and go inside it.

   <img src="https://github.com/sahnishant/label-studio/assets/134548275/6bc11a9e-b3eb-4d77-86bb-291df8d6eae7" alt="image" width="45%" height="45%">

   - Download the [folder](https://github.com/sahnishant/label-studio/archive/refs/heads/main.zip) 
   - Extract all files inside the folder you created above. 
   - Copy the file server.py from github
   - Copy all images given to you
   - Your final folder should look like this:


   <img src="https://github.com/sahnishant/label-studio/assets/134548275/7229886d-9c1b-4831-be8e-ae2bad7706c1" alt="image" width="45%" height="45%">

5. Open terminal by right clicking inside the folder. You can also open the command prompt.

   <img src="https://github.com/sahnishant/label-studio/assets/134548275/c712e95c-8ef9-4358-a4ad-476dfb5fdb4a" alt="image" width="45%" height="45%">
   
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
