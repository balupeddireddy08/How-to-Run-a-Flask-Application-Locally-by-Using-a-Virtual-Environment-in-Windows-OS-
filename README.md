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
<h3>Create virtual Environment using Command prompt</h3>
1. Installation of Python and pip :<br>
