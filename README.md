# Author:  ->  Amit Yadav


#  Version Control Using Git and the Command Line


1.git init    --> git initialise  (working directory)

2.git add .   --> added all the file to staging area.

3.git status   --> check status of added file.

4.git commit -m "first commit"   -->making commit to send the file from staging area to local repository.

5.git log   --> check commit status

6.git checkout  -->if your code in your file changed by accidently you can return to your last commit.

# Github and remote repository


1.login in your github account.

2.Create new repository by clicking on new repository.

3.If you are not doing any brand new technology then make your repository to public.

4.create repository by clicking on create repository.

5.now you can push your local repository to github.
  
 <t> i.by set up in desktop.
  
 <t>ii.by using https or ssh url.

6.now inorder to push existing repository from the command line type the following command on your cmd make sure you are in your project directory.
 
   i. git remote add origin {paste url link of your git hub repositroy}.<br>
   
  ii. git push -u origin master/main.   -->this will push your project to github now you can see your project by refreshing github repository page .<br>



# gitignore
 
1.create gitignore file by typing command
  
   i. touch .gitignore <br>
   
   ii. open .gitignore  ->you can write the file name that you want to ignored while pushing the file to remote repository <br>
   
   iii. git init <br>
   
   iv. git add. -> this will added all file to gitignore.<br>
   
   v. git status<br>
   
   vi. git rm --cached -r .  -> remove all file from gitignore file.<br>
   
   vii. git commit -m "first"

2. https://github.com/github/gitignore  you can check out here what are the file that you no need to push into your remote repository.
   accordingly you can add it in your gitignore file.
   
# Cloning

1.Go to the repository that you want to clone.<br>

2.copy url.<br>

3.go to your local machine.<br>

4.go to your directory where you want to clone the project.<br>

5.open cmd type command "git clone {past the coppy url}" hit the enter button.<br>

6.it will take some time then you can check the project in your local machine.<br>

7. you can check all the previous commit by hiting the command "git log".<br>

# Branching and Merging

1.go to your local repository.<br>

2.if you want to create new branch just type "git branch xxxx".<br>

3.now you can check out what branches you have by just typing "git branch".<br>

4.now if you wnat to switched into "xxxx" branch simply type "git checkout xxxx".<br>

5.make some changes in your code type " git add ." --> ' git commit -m "new changes" '.<br>

6.check "git  log" you can see here all the previous commit branch wise.<br>

7.now if you are go back to your master branch "git checkout master/main" you can see master branch remain unchange.<br>

8.if you like to merge changes "git merge master/main".<br>

9.type "git push origin master -u".<br>

10.now you can check the file all to your remote repository and for branch go network and check insight.<br>
