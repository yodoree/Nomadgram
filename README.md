#instagram Clone coding

Cloning Instagram with Python Django and React / React Native

pip3 install cookiecutter

pipenv shell

cookiecutter https://github.com/pydanny/cookiecutter-django

git init
git remote add origin {YOUR_GIHTUB_URL}
git pull origin master
git add .
git commit -m "First commmit"
git push origin master

pipenv --three 가상환경(virtual environment) 만들기
pipenv shell
pipenv install -r requirements/local.txt

In case of an error try this:
pip install -U setuptools
pip install -U pip
pipenv install -r requirements/local.txt