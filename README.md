
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
  
  i.by set up in desktop.
  
  ii.by using https or ssh url.

6.now inorder to push existing repository from the command line type the following command on your cmd make sure you are in your project directory.
 
   => git remote add origin {paste url link of your git hub repositroy}
   => git -u origin master/main.   -->this will push your project to github now you can see your project by refreshing github repository page .



# gitignore
 
-> create gitignore file by typing command
  
   => touch .gitignore
   => open .gitignore  ->you can write the file name that you want to ignored while pushing the file to remote repository.
   =>git init
   =>git add. -> this will added all file to gitignore.
   =>git status
   =>git rm --cached -r .  -> remove all file from gitignore file.
   =>git commit -m "first"

-> https://github.com/github/gitignore  you can check out here what are the file that you no need to push into your remote repository.
   accordingly you can add it in your gitignore file.
