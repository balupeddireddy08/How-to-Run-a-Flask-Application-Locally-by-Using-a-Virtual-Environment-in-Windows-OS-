# How-to-Run-a-Flask-Application-Locally-by-Using-a-Virtual-Environment-in-Windows-OS-
## Easily create a virtual world for your projects
<h2>What is a Virtual Environment?</h2>
A virtual environment creates separate space for a project with its dependencies at a definite place. This environment is distinct to the specific project and doesn't interfere with other project dependencies.<br>
<h2>Advantages of Virtual Environment?</h2>
>> A virtual environment creates it's own dependencies and space instead of disturbing the local environment.<br>
>> After activating the virtual environment, it provides the facility to freeze the current state of the environment packages.<br>
>> Virtual Environment provides a facility to install any packages as well as notebooks.<br>
<h2>Motivation</h2>
Everybody might come across this term called Virtual Environment. For the people who work with multiple projects in the localhost. Due to the requirements of each project, there is more chance of jumbling all packages in the same localhost. This leads to the improper organization of all the packages and mixing up of all packages. This is a time-consuming process to debug the projects.<br>
If you want to check and run the other's project in your localhost. You need to install dependencies and packages related to the corresponding project. So, While working with multiple projects. It is better to create Virtual Environments instead of disturbing local environments and dependencies.<br>
<h3>In simple words, Let me give you an example :</h3>
So, You have created a flask app which is an interface of the Machine Learning model and website. You used scikit_learn package version 0.21.3 to create pickle files. Your friend asked you to check his/her project which is having the pickle files containing scikit_learn package version 0.23.1. To help your friend, you have installed all the requirements of that project and you helped your friend. But, The first project won't work. Because you have installed some other versions of packages. So you need some time to re-install your packages and make your first project work. Instead of facing these types of issues, it's better to create virtual environments while working with multiple projects.<br>
<h2>Getting Started</h2>
This article guides you to create a virtual environment and run your flask application in your localhost containing the Windows Operating system by using various methods:<br>
>> Command prompt<br>
>> Anaconda prompt<br>
>> Ubuntu application<br>
## Create virtual Environment using Command prompt
1. Installation of Python and pip :<br>
Open the command prompt. Check your laptop is having Python as well as pip or not. Use the below commands to check them. you should write two hyphens as in the image. The latest version of python contains pip pre_installed only for older versions you need to install manually.<br>
>> python - version<br>
>> pip - version<br>
If you don't have python in your computer download it here and add the path to the environment variables. If you don't have pip installed in your computer download it here to a folder on your computer and save it with the same name "get-pip.py". Open a command prompt and navigate to the folder containing the get-pip.py installer.<br>


Run the following command:<br>
python get-pip.py
2. Navigate to the directory contains the Flask application.<br>
Make sure that your flask folder containing all the files required to run on your laptop.<br>
Use these commands to navigate the command prompt:<br>
To navigate one step back from the current path use:<br>
cd..
To move into the folder from the current path use:<br>
cd<space>[specified_folder]
This is the path of my flask app on my laptop.<br>
Using the above commands and navigate to the flask app folder.<br>
( or )
2. Clone the directory from GitHub.<br>
If you don't have Git installed in your Computer download it here. Clone the repository by using the following commands. On running the first command a folder is created(clone) in your specified path.<br>
git clone [link_of_repository]
cd [repository_name]
3. Check the list of files in your flask app folder by using the following command:<br>
dir
4. Install Virtual environment in your folder by using the following command:<br>
pip install virtualenv
5. Name your virtual environment by using the following command:<br>
virtualenv [virtual_environment_name]
6. Navigate to your virtual environment folder and there you will see scripts folder.<br>
That is the folder which contains all operations of Virtual environment and "activate" your venv by using the command:<br>
activate
You will see a name on the left side of the terminal in brackets. By this, A virtual environment is activated.<br>
## Your Job is done…!!!🔥🔥🔥
7. If you want to run your flask application in your local, you need to install all the requirements in the Virtual environment and these dependencies do not reflect the dependencies in your laptop.<br>
Make sure, you must have a requirements text file which contains all dependencies along with the version.<br>
8. Navigate back to the folder which contains requirements.txt file and install all the requirements in your virtual environment by using the following command:<br>
pip install -r requirements.txt
9. Run your python file to see your application by the following command:<br>
python [python_file_name].py
10. Copy the URL and paste in the Browser. You will see the flask application running in your localhost.<br>

## Create Virtual Environment using Anaconda prompt
Open the Anaconda command prompt. Check your laptop is having Python as well as pip or not. Use the below commands to check them.you should write two hyphens as in the image. The latest version of python contains pip pre_installed only for older versions you need to install manually.<br>

python - version
pip - version
View the list of available version by using the following command:<br>
conda search python
To install a specific version of python by using the following command:<br>
conda install python=[version]
Install pip in Anaconda command prompt by using the following command:<br>
conda install pip
2. Navigate to the directory contains the Flask application.<br>
Make sure that your flask folder containing all the files required to run on your laptop.<br>
Use these commands to navigate the Anaconda command prompt:<br>
To navigate one step back from the current path use:<br>
cd..
To move into the folder from the current path use:<br>
cd<space>[specified_folder]
This is the path of my flask app on my laptop.<br>
Using the above commands and navigate to the flask app folder.<br>
( or )
2. Clone the directory from GitHub.<br>
If you don't have Git installed in your Computer download it here. Clone the repository by using the following commands. On running the first command a folder is created(clone) in your specified path.<br>
git clone [link_of_repository]
cd [repository_name]
3. Check the list of files in your flask app folder by using the following command:<br>
dir
4. Install Virtual environment in your folder by using the following command:<br>
conda install virtualenv
5. Name your virtual environment by using the following command:<br>
virtualenv [virtual_environment_name]
6. Navigate to your virtual environment folder and there you will see scripts folder.<br>
That is the folder which contains all operations of Virtual environment and "activate" your venv by using the command:<br>
activate
You will see a name on the left side of the terminal in brackets. By this, A virtual environment is activated.<br>
## Your Job is done…!!!🔥🔥🔥
7. If you want to run your flask application in your local, you need to install all the requirements in the Virtual environment and these dependencies do not reflect the dependencies in your laptop.<br>
Make sure, you must have a requirements text file which contains all dependencies along with the version.<br>
8. Navigate back to the folder which contains requirements.txt file and install all the requirements in your virtual environment by using the following command:<br>
pip install -r requirements.txt
9. Run your python file to see your application by the following command:<br>
python [python_file_name].py
10. Copy the URL and paste in the Browser. You will see the flask application running in your localhost.<br>

## Create Virtual Environment using Ubuntu application
This method is mainly recommended to install packages and notebooks not to do projects. You can follow a similar process to create a Virtual Environment in Linux.<br>
Open Windows Powershell App and run it as administrator.<br>

1.To do that First, enable the "Windows Subsystem for Linux" feature in Windows Powershell App by using the following command.<br>
Enable-WindowsOptionalFeature -Online -FeatureName Microsoft-Windows-Subsystem-Linux
After it is prompted, Restart your laptop.<br>
2. Download the Ubuntu App from the Windows Store. Ubuntu 20.04LTS is used in the article to show demo.<br>
Lunch Ubuntu App and make sure that Windows PowerShell is opened. Because Ubuntu App is running on behalf of the Windows PowerShell App.<br>
3. Set up a new user name and password and remember your password. It will be used further to install packages.<br>
To paste the commands in Ubuntu use:<br>
Right-click
Ctrl +Shift+v
4. Update and upgrade your Ubuntu packages by using the following command:<br>
sudo apt update && sudo apt upgrade
5. Now, Install all the dependencies of python to create a virtual environment and pip in the Ubuntu App by using the following commands:<br>
sudo apt-get install -y libstdc++6 python-setuptools
sudo apt-get install python3-pip
6. Clone the repository by using the following commands. On running the first command a folder is created(clone) in your specified path.<br>
***git clone [link_of_repository]***
***cd [repository_name]***
7. Install Virtual environment in the flask app folder by using the following command:<br>
***sudo pip3 install virtualenv***
8. Name your Virtual Environment accordingly by using the following command:<br>
***virtualenv [virtual_environment_name]***
9. Activate Virtual Environment by using the following command:<br>
***source venv/bin/activate***
## Your Job is done…!!!🔥🔥🔥
10. Install requirements in the virtual environment.<br>
If you want to run your flask application in your local, you need to install all the requirements in the Virtual environment and these dependencies do not reflect the dependencies in your laptop.<br>
Make sure, you must have a requirements text file which contains all dependencies along with the versions.<br>
***pip install -r requirements.txt***
11. Run your python file to see your application by the following command:<br>
***python [python_file_name].py***
12. Copy the URL and paste in the Browser. You will see the flask application running in your localhost.<br>
This article is helpful for you while doing projects and courses. I suggest following this way which differentiates all your system dependent projects and places them in an organized manner.<br>
I hope, You do well and correct me if anything is wrong…!!! 🤝🤝🤝
# Happy Learning!😎
