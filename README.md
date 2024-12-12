# job_coverletter_gen
Generate a Job cover letter based on your CV that's in pdf format using locally running Ollama. 

## Steps to start
- install Ollama locally (download [here](https://ollama.com))
- first install poetry package for creating virtualenv and package management as well. 
- setup the virtual env using `poetry shell` and it should also install all the required packages needed.
- in addition to the above step, please run:
    ``` shell
    pip install -r requirements.txt
    ```
    was unable to install `torch` package using `poetry` ¯\_(ツ)_/¯
- to use the python venv in the notebook create the ipykernel using this command to use the installed dependency packages:
    ``` shell
    python -m ipykernel install --user --display-name $(echo `pwd`) --name $(echo `pwd` | sed -r 's$/$_$g')
    ```