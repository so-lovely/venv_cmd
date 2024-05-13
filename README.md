# This descriptions for MACOS

## In brew website,paste them at vscode terminal
## You should install brew and other things in vscode terminal

### If you install brew at first, make sure that you press ENTER/RETURN
```
brew install pyenv
touch ~/.zshrc
nano ~/.zshrc
export PYENV_ROOT="$HOME/.pyenv"
export PATH="$PYENV_ROOT/bin:$PATH"
eval "$(pyenv init --path)"
```
### After copy and paste it, press the key ^O + ^X for save
### And then following the code below
```
source ~/.zshrc
```
```
python3 -V  | python3 --version
pyenv versions
pyenv install (e.g) 3.10.12

git clone https://github.com/pyenv/pyenv-virtualenv.git $(pyenv root)/plugins/pyenv-virtualenv

pip3 install virtualenv | brew install virtualenv
virtualenv [file_name]
```
## pyenv local denotes you can use the different python versions each of dir
```
pyenv global [python_version]
pyenv local [python_version]
```
