# Lab-1
## Debugging and GitHub

This is the first lab for COMP 167 Computer Program Design at North Carolina A&T State University

Instructor: Dr. Kelvin Bryant - ksbryant@ncat.edu

The objective of this lab is to introduce you to git and GitHub, two tools that will be used _extensively_ this semester, as well as the NetBeans IDE.

### What is Git?

Git is a system that allows developers to store multiple _versions_ of a single project, called **branches**. It also allows developers to keep their **local** copy of code up to date with **remote** copies. This has many advantages, mainly that it provides backup copies of code, and makes it easy to _collaborate_ with other developers in the same office, or across the world.

Git stores projects in special directories called **repositories**. A repository is nothing more than a directory, or folder, that has its changes tracked by git. Therefore, most small projects (and every project in this class) should be contained in a single git repository, or folder. You may not know this yet, but you've already created your first git repository! It is called "Lab-1-YOUR-USERNAME" and you're looking at the **remote** copy of this repository _right now_. This remote copy is hosted on GitHub.

### What is GitHub?

GitHub is a service that hosts remote repositories for millions of developers around the world. Companies like Apple, Google, Microsoft, RedHat, Adobe, Twitter, PayPal, and Facebook use GitHub to host their code. GitHub is also the world's largest host of open source projects, making it a treasure trove for young developers to learn from millions of projects.

In this class, we will complete all programming assignments on GitHub, this will allow TA's to easily check your work, and will protect your work from loss should anything happen to your computer.

### Setiing Up for the Lab

Now that you know some of the basic terms, lets move into this lab. The first thing you must do is **clone** the repository, or create a **local** copy of the repository on your computer. to do this, you will need to launch the **git bash** app on your lab computer. If you are using your own computer, install git by following the instructions for your operating system on [the git website](www.git-scm.com).

   1. Clone the repository.
      * After opening git bash, type the command `cd Documents` and press enter. This will change the current directory in your terminal to your Documents directory.
      * Next, create a directory to hold all of your git repositories. Type the command `mkdir COMP167` and press enter. Now, if you type the command `ls` and press enter you should see your new _COMP167_ directory listed. Change to this directory by entering `cd COMP167` and pressing enter.
      * You will need to acquire the link to your remote git repository. Click the green _Clone or Download_ button above these instructions and copy the link provided.
      * Finally, you can clone your repository by entering `git clone [PASTE-LINK-HERE]`. Note that the square brackets are only to separate your information from the actual command you should type. After pasing your link, you command should look something like this `git clone https://github.com/NCAT-COMP167-Spring2018-Lab-1-ccannon94.git`.
   2. Open the repository and project.
      * You must now navigate to your repository in git bash. First, run the `ls` command to view the contents of your current directory. You should only see one subdirectory, this is the repository you have just cloned. To navigate to your repository, run `cd [REPOSITORY-NAME-HERE]`.
      * Now that your repository is open in git bash, it's time to open NetBeans, the IDE we will use in COMP167.
      
### What is an IDE?

An IDE, or an Integrated Development Environment, is a tool developers use when writing software. Good IDE's endeavor to make often repeated tasks as easy as possible for developers, as well as help developers avoid errors by providing services like autocompletion, linting, and debugging.
