# ExpenseTracker
This is an startup project to keep track of daily household investment

Follow the steps to start with git repository.

Prequisites for end to end development.

1- Java 1.8

2- Mysql 5.5

3- Eclipse Kepler(32/64bit)

4- OS(Ubuntu/windows)

5- Git

6- Git Client(Smart git for check in/out)

7- Maven 3

8- Tomcat(Optional as currently we are not going to develop web application but may be in future) .




Follow below steps to get code base.


1- Fork local repository from the original repository.

2- Create new folder for git repository $ mkdir ~/ExpenseTrackerRepo

3- Go to created git repository folder $ cd ~/ExpenseTrackerRepo

4- Clone github ExpenseTracker repo $ git clone git@github.com:erbharat/ExpenseTracker.git

5- Go into your ExpenseTracker repo $ cd fractal

6- Initialize git flow (you already have installed git flow) $ git flow init

7- Check your branch statuses $ git branch -a

8- (Should display all available branches *develop, master, remote branches as well)

9- Configure your git push option to follow branch name $ git config --global push.default current

10- Modify your code and commit your changes $ git commit -am "Your comment"

11- Push your code to develop branch $ git push -u origin develop. This is necessary to do only on your first push, every other push should be like $ git push

12- To pull the latest code from the branch you're currently at, use $ git pull. If you get error or warning on pull, add -u as in push with remote name and branch $ git pull -u origin 

13- Follow git documentation for more understanding.
