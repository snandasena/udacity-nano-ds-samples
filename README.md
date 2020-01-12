### Running instructions for linux environment
#### Prerequisite to have be installed
**01.** Python3.6(Python3)  
**02.** Virtualenv  
**03.** Requirements that are in **requirements.txt** 

##### Step 01: Clone the project to your workplace
If you are using a ssh key for GitHub, please use flowing git command to clone the project.
```bash
git clone git@github.com:snandasena/udacity-nano-ds-samples.git
```
Otherwise use HTTPS git method to clone the git repositories.
```bash
git clone https://github.com/snandasena/udacity-nano-ds-samples.git
```
##### Step 02: Create a Python3.6(Python3) virtual environment inside the project root directory
Here I assumed you are in the project root directory and here **"."** is represent the current directory.
```bash
virtualenv -p python3.6 .
```
Then activate the python virtual environment
```bash
source bin/active
```
##### Step 03: Install requirement that are in **requirements.txt** file.
Here is the command to Python requirements from a text file.
```bash
python -m pip install -r requirements.txt
```