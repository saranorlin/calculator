# this is my django practice calculator 

## Getting started
1. Install homebrew
2. `brew install postresql@15`
3. `python3 -m pip install Django`
4. `brew install openssl pyenv`
5. Add to your .zshrc file
```
export LDFLAGS="-L/opt/homebrew/opt/openssl@3/lib"
export CPPFLAGS="-I/opt/homebrew/opt/openssl@3/include"

eval "$(pyenv init -)"
```
6. `pip3 install pipenv`
7. cd into the project folder and `pipenv shell`
8. `export DJANGO_SETTINGS_MODULE=mycalculator.settings`
9. `python3 manage.py runserver `

- https://docs.djangoproject.com/en/4.2/intro/tutorial02/#database-setup
