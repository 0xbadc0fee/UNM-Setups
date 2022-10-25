# UNM / Github
Using git and github
Here is a quick video on what github is. Please create an account on github and create a new repository. WHEN YOU SIGN UP FOR GITHUB, PLEASE DO NOT USE YOUR UNM EMAIL, YOU WANT THIS ACCOUNT TO EXIST AFTER YOU GRADUATE. The idea is that you KEEP ADDING CODE THROUGHOUT YOUR CAREER AS A PROGRAMMER. Feel free to name your new repository anything you want (please keep it appropriate). Also, initialize your git repo with a README.md. You will be writing things like what kind of code the git repo has, what does the code do, how to use the code, etc..., to your README file.

All your github repositories (git repos) will be public, as potential employers can see the code that you have created. This will show that you can work in groups and your git repos will be the proof.

Once you have created your git repo in github, open a terminal and type:

    git clone https://github.com/<github username>/<git repo name>
    cd <git repo name>
Where <github username> is your github username and <git repo name> is the name of the git repo that you have just created. After this is done, type:

    vim hello.cpp
Write a simple hello world program and add it to your git with this command:

    git add hello.cpp
(optional) you may type

    git status
And may find that git is keeping track of executables such as a.out, and other files, you can create a .gitignore (a hidden file), this file will tell git to not keep track of these files. You can create one that will not keep track of a.out this command:

    vim .gitignore
Inside of the file it should look like this:

    .gitignore
    a.out
Notice how I also added .gitignore, that is because .gitignore will not ignore itself. (end optional)

Now that you have added a program to your git and added it, you need to write a commit that documents what you have done. Here is an example:

    git commit -m "Added a program called hello.cpp that prints Hello world!"
The only that should vary between git commits is what is between the double quotes. Please make your git commits meaningful. Not only will I be taking a look at your git commits, but fellow students as well (AND POTENTIALLY RECRUITERS). Lastly, type this command to upload changes to your git repo:

    git push
You will be asked to enter your github username and password and BAM! you will have updated your repo, type this command to see your history of commits:

    git log
Once you have created your git repo and added hello.cpp and updated your git repo (your repo should have two commits), you are done!
