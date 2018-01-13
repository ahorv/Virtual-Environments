# Virtual-Environments
all my virtual environments I have used

see: https://conda.io/docs/user-guide/tasks/manage-environments.html#sharing-an-environment

## Usage:
To export an virt environment use in your activated virtual environment:
env export > skycam_environment.yml

To import an virt environment from a \*.yml file use:
- Save the \*.yml file under C:\Users\username\Anaconda3\envs
- Activate the root Anaconda prompt and type:
- conda env create -f skycam_environment.yml -n skycam


## skycam (13.01.2018)
This virt env is used for any programming involved with opencv eg.:
- optflow.py

installed packages (running under Windows)
- opencv 3
- matplotlib via 'matplotlib-2.1.1-cp36-cp36m-win_amd64.whl' from 'https://www.lfd.uci.edu/~gohlke/pythonlibs/#matplotlib'
  saved the file under ...\Local\conda\conda\envs\skycam. Than activate the virt env skycam change to the directory with
  the downloaded file and do : pip install matplotlib-2.1.1-cp36-cp36m-win_amd64.whl

- opencv 3 via weehl which I had to download from:
- pip install opencv_python-3.4.0-cp36-cp36m-win_amd64.whl

## pvis (13.01.2018)
This virt env is used for project visualizer (Django project)

installed packages (running under Windows)
- django : pip install django==2.0.1
- exifread : installed in Anaconda prompt via pip


## pipic (13.01.2018)
This virt env is used for the Django project pipic (timlapse photography with raspberry pi)

installed packages (running under Windows)
- pip install -U celery
- pip install django==2.0.1


