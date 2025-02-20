February 5th Notes

***another way to initialize a repository***...make sure you have an open file to send to github before you do this...
$ls -a
$git init
$ls -a



A- ADD
C- COMMIT
P- PUSH


$git . add.....it adds all changes to staging
why do we need to add things to changes?
it is a prerequisite to commit. once we commit it is saving it permanetly. we don't wont commit(stage) broken code. 
when you start working in the industry you will be using this....
the commit messages should show the changes you made. 

*when you make changes to your code*

$git commit -m "add heading to webpage"
commits it for version control. it hasnt been pushed to github.
*people who write laws will use git or authors to build different versions to their chapters of endings. so its not a way to get your code on the internet it is a way to save different versions of your work.*

in source control...you click on the graph to see all your changes or when you need to make changes. 

using the A and the C work flow
***every time you add a stable feature you should commit and make sure to write descriptive comments for your commits to track all of your changes...you can also roll your code back if you need to. using copy and paste from your source control but will learn another way

Push= getting your work to github

Work flow step by step:
1. create a folder and name it locally
2. open vs code
3. create an index.html file as usual and add boilerplate content
4. go to new terminal
5. .git init to create a new repository
6. git add . to add my changes
7. git commit -m "      "     to commit my changes. and describe your work correctly.
8. then go to github
9. create a new repository. and name NO README FILE. and name it the exact name what what you were working on in vscode.
10. copy the code block at the bottom that says "push an existing repository from the command line" and paste it into the terminal





***BRANCHING***

$git switch -c dev

$git checkout dev

instructions for the assignment:
git branch dev 2
git branch
git checkout dev2



git switch -c dev3 this will create and switch all in one commands

you can use whichever you want for the assignment
the c stands for create
(if you need to create a branch its.....git switch -c)
(if you need to switch to an existing branch its......git switch)

**Echo**
it is for creating files and it returns a string
$ echo "hello"
you will use this on back end developing...it could be replaced with touch to create a a new file. 

**merging branches**
when we take the dev branch and the main branch and merge them together. 
at 30 mins left or presentation to watch step by step
$ git branch
$ git checkout test and git switch do the same thing. 
(checkout is older so you dont need to use it but you may run into a company that still uses the older version so just be aware of the command)

![[Pasted image 20250206194250.png]]

in assignment anywhere it says checkout you can use switch.
the assignment also asks you to use echo. ![[Pasted image 20250206194535.png]]
this is called streaming off of the hello. its just how you get things to print out. you could also replace it with touch to create a new file. 
![[Pasted image 20250206195802.png]]


made a commit and added a branch 

![[Pasted image 20250206195842.png]]

![[Pasted image 20250206195918.png]]
then we merge it
![[Pasted image 20250206195943.png]]
you can see it here


rebase...can destroy come information thats why he demands we dont use it. A senior developer may tell you to rebase bc there was a wierd commit. Other than that dont use it. It could delete some commits/history. and will merge it into one single line of work. or if you do it in the wrong direction it could put it in the wrong direction. Also** make sure you merge to the main branch.** never merge to the dev. if you do this you will no longer have the commit history to go with your main. or merge it to the branch that you want to bring your info to when you done. this is usually your main branch. sometimes you could have two main branches one for testing and one being presented. make sure you always pick the branch to be displayed to your users is the one you merge everything to. 


for assignment ....create a read.me file to save your screen shots into. 