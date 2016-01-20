#Work with Virtual Environment

#Objective
  Introduce the Virtual Environment in python

#Requirement
1. Python;

#What is Virtual Environment
  A tool that you creat a environment box.
  In the box you can install and use different VERSION of one python package without disturb each other.
  e.g. In one box I can use django1.5, In another box a can use django1.9. Both in one PC.

#Why we should use Virtual Environment
  Python packages are always developing, the Version is always different when you work youself or with your mates.
  You may need move from one version to another version from time to time, and you can not delete and reinstall every time.
  So you need virtual environment to work with different version of packages.

#Headless quick start
  1. install via pip
    ```
    $ pip install virtualenv
    ```
  2. Create a virtual environment for a project
    ```
    $ cd your_project_folder
    $ virtualenv myvenv
    ```
  3. activated the environment
    ```
    $ source myvenv/bin/activate
    ```
  4. quite the environment
    ```
    $ deactivate
    ```
  4. reference source, [link](http://docs.python-guide.org/en/latest/dev/virtualenvs/)

#Content
  None

#Issue


#Notes
