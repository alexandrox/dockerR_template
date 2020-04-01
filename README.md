# dockerR_template

#### This repository host a template to launch a workstation with RStudio server:   
* Folder for notebooks (R Notebooks) to report/develop analysis.   
* Folder for data to host data, files in this folder are not sync to the git repository.  
* Folder for code to host scripts to populate data folder.  
* Container to reproduce workstation environment using [docker.](https://docs.docker.com/)  

#### To start
Clone the repository `git clone`, and populate the data folder

##### General view of the repository:
    |-- .gitignore
    |-- LICENSE.md
    |-- README.md
    |-- docker-compose.yml
    |-- code
        |-- script-to-populate-data_dir.sh 
    |-- data
        |--.gitignore
    |-- docker/
        |--Dockerfile
    |-- notebooks
    
    
##### Launch Docker