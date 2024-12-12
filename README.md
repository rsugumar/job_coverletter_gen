# job_coverletter_gen
Generate a Job cover letter based on your CV that's in pdf format using locally running Ollama.

## Steps to start
- install poetry
- setup the virtual env using `poetry install` and it should also install all the required packages needed.
- in addition to the above step, please run `pip install -r requirements.txt` also.
- ``` python -m ipykernel install --user --display-name $(echo `pwd`) --name $(echo `pwd` | sed -r 's$/$_$g') ``` to use the python kernel in the notebook. Pls choose this newly created kernel to use the dependence packages.