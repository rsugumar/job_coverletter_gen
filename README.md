# job_coverletter_gen
Generate a Job cover letter based on your CV that's in pdf format using locally running Ollama. 

## Steps to start
- install Ollama locally (download [here](https://ollama.com))
- install poetry
- setup the virtual env using `poetry install` and it should also install all the required packages needed.
- in addition to the above step, please run:
    ``` shell
    pip install -r requirements.txt
    ```
- to use the python venv in the notebook create the ipykernel using this command to use the installed dependency packages:
    ``` shell
    python -m ipykernel install --user --display-name $(echo `pwd`) --name $(echo `pwd` | sed -r 's$/$_$g')
    ```