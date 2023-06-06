### flake8
```bash
pip install flake8-import-order flake8-builtins flake8-quotes pep8-naming flake8-bugbear flake8-commas flake8-variables-names flake8-functions flake8-class-attributes-order flake8-expression-complexity flake8-cognitive-complexity
```
### Create user, setup SSH
```bash
sudo apt-get update ; \
sudo apt-get install -y vim mosh tmux htop git curl wget unzip zip gcc build-essential make
```
### Install python 3.11
```bash
wget https://www.python.org/ftp/python/3.11.3/Python-3.11.3.tgz ; \
tar xvf Python-3.11.* ; \
cd Python-3.11.3 ; \
mkdir ~/.python ; \
./configure --enable-optimizations --prefix=/home/www/.python ; \
make -j8 ; \
sudo make altinstall
```
setup
```
sudo /home/www/.python/bin/python3.11 -m pip install -U pip
```
