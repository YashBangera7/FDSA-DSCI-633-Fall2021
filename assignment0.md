[<img width=900 src="https://github.com/YashBangera7/FDS_DSCI-633_Fall2021/images/image1.jpg?raw=yes">](https://github.com/YashBangera7/FDS_DSCI-633_Fall2021/Readme.MD)   


## Python Basics

### 0. Learn Python basics on [Codecademy](https://www.codecademy.com/learn/learn-python) (free version), [w3schools](https://www.w3schools.com/python/), and the [tutorial from the textbook](http://www.cse.msu.edu/~ptan/dmbook/tutorials/tutorial1/tutorial1.html)
 - Skip this step if you already know how to code in Python.
 - If you are seeking for more practices, [https://www.w3resource.com/python-exercises/](https://www.w3resource.com/python-exercises/) has plenty of exercises.

### 1. Install Python on your local machine.

 - Install [conda](https://docs.conda.io/en/latest/miniconda.html) with Python 3.8+.
 
### 2. Install required packages.
 - Open terminal.
 ```
 conda install scikit-learn
 conda install pandas
 ```
 
### 3. (Optional) Install an IDE.
 - [Pycharm](https://www.jetbrains.com/pycharm/) community version.
 

## Github Basics

### 0. Install [Git](https://git-scm.com/downloads) and create your [Github](https://github.com/) account.
 - Skip this step if you already have one.

### 1. Create a new PRIVATE repository called **FDS_DSCI-633_Fall2021** under your Github account.
 - (1) Click on the **new** button:
 ![](https://github.com/YashBangera7/FDS_DSCI-633_Fall2021/images/image2.png?raw=yes)
 
 - (2) Initiate the new private repo:
 ![](https://github.com/YashBangera7/FDS_DSCI-633_Fall2021/images/image3.png?raw=yes)

 - (3) Click on Settings:
 ![](https://github.com/YashBangera7/FDS_DSCI-633_Fall2021/images/image4.png?raw=yes)

 - (4) Click on Manage Access:
 ![](https://github.com/YashBangera7/FDS_DSCI-633_Fall2021/images/image5.png?raw=yes)
 
 - (5) Invite the instructor and the TA as collaborators (GitHub ID: **uberize, YashBangera7**):
 ![](https://github.com/YashBangera7/FDS_DSCI-633_Fall2021/images/image6.png?raw=yes)

### 2. Clone the **DSCI-633** repo to your local machine.
 ![](https://github.com/https://github.com/YashBangera7/FDS_DSCI-633_Fall2021/images/image7.jpg?raw=yes)
 ```
 git clone THE-COPIED-URL
 ```

### 3. Save username and token in git.
 - Create your personal access token on [this page](https://github.com/settings/tokens)
 - Copy the generated token.
 - In terminal:
 ```
 git config --global credential.helper manager
 ```
 - When running this command, the first time you pull or push from the remote repository, you'll get asked about the username and your token (NOT Password!). Afterwards, for consequent communications with the remote repository you don't have to provide the username and password.

### 4. Working with a github repo.
 - (1) Go to the local directory of the **FDS_DSCI-633_Fall2021** repo.
 - (2) Pull from Github so that the content on your local machine is updated with the remote server of Github:
 ```
 FDS_DSCI-633_Fall2021> git pull
 ```
 - (3) Work on your local machine (add/remove/edit files under FDS_DSCI-633_Fall2021/).
 - (4) Commit to the remote server of Github (upload local changes).
 ```
 FDS_DSCI-633_Fall2021> git add .
 FDS_DSCI-633_Fall2021> git commit -m "YOUR COMMIT MESSAGE"
 FDS_DSCI-633_Fall2021> git push
 ```
 
 ### 5. Add your information to [Google sheet](https://docs.google.com/spreadsheets/d/1q7tw0On2aCCHZEuJ8KAYOgad2yPxS8U1aWb81jsrU0k/edit?usp=sharing)
 - Add your github repo url (along with your RIT identifier and Github ID) to the Google sheet.
 - Make a self-evaluation on your current knowledge/expertise in coding, Python, and machine learning. This information will ONLY be used to decide your study group.