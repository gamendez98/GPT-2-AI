# Installation

## Creating virtualenv

Start by updating the packages list and installing the prerequisites:
```
sudo apt update
sudo apt install software-properties-common
```
Next, add the deadsnakes PPA to your sources list:
```
sudo add-apt-repository ppa:deadsnakes/ppa
```
When prompted press Enter to continue:

Once the repository is enabled, install Python 3.7 with:
```
sudo apt install python3.7
```
At this point, Python 3.7 is installed on your Ubuntu system and ready to be used. You can verify it by typing:
```
python3.7 --version
```

Now install virtualenv
```
python3.7 -m pip install --user virtualenv
```

Create the virtual enviroment
```
python3.7 -m virtualenv venv
```

Activate the enviroment
```
. venv/bin/activate
```

Now you can use python3.7.x as your default python
```
python --version
```

With the virtual enviroment activated install follow the steps on [the instalation file](gpt-2/DEVELOPERS.md)