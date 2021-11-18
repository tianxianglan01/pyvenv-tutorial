# pyvenv-tutorial

### Steps

- See current python version
python --version

- create a venv directory where 'name' is what we want to name our venv

python -m venv 'name' 

- activate venv

'name'\Scripts\activate.bat

- create requirements.txt which will allow other users to use the same packages you are using

pip freeze > requirements.txt

- deactivate venv

deactivate 

- delete venv (just delete directory of venv)

rmdir 'name' /s 

####
Don't forget to check where your current directory is 
