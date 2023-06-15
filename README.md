Web App for project "Data Mining the Water Table"


Steps to create and build package:

1. create folder where we store our app data
2. open terminal in the folder and open vscode using 'code .'
3. create new vitual environment using coand 'conda create -p venv python==3.9 -y'
4. create README.md file
5. create repository on github
6. use following commands to setup the repository

    git init
    git add README.md
    git commit -m "first commit"
    git branch -M main
    git remote add origin https://github.com/vikrantmohite19/Data_Mining_Water_Table-Web_App.git
    git push -u origin main

7. create setup.py and requirements.txt
8. create source folder as 'src' and a file inside it as '__init__.py'
9. run command 'pip install -r requirements.txt'. ugrade pip if required using 'python -m pip install --upgrade pip'
10. created exception.py and logger.py
11. Created new folder 'notebook' and copied all ipython files into the folder. 
12. Then to run ipython notebooks , had to run the command in terminal "conda install ipykernel --update-deps --force-reinstall" to install ipykernal.
13. Created inside the folder 'src' created exception.py, logger.py, utils.py
14. Inside src, created new folder 'pipeline'. Inside 'pipeline created __init__.py, predict_pipeline.py & train_pipeline.py.
15. Inside src, created new folder 'components'. Inside 'components' created __init__.py, data_ingestion.py, data_transformation.py, model_trainer.py.

