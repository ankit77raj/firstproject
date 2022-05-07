What is Git and Github?

version control?

1st commit - I create a project. 
2nd commit - Alankar changes the backend code.
3rd commit - Pooja again changes the way API is written. -> revert 4th commmit it to this commit 
5th commit - Laurence fixes the issue and commits again. -> code is here

4th commit - Laurence changes a part which accidently breaks the system - Error was introduced here. Our app is not working.

Why git? - to have a flexibility of the version of your code and to collaborate among your teammates.



In college - 

Without git
- project1.pdf
- project_final.pdf
- project_final2.pdf 
.
.

Using git
- project.pdf -> 1st commit 
- make changes in project.pdf -> 2nd commit 
- make changes in project.pdf -> 3nd commit 




Initialing the git repo
- `git init`

- `git status`
- tells us the status of our project




- make a file and write your introduction



What is `git add .`, `git commit -m message` , `git push` ??

- `git add .`
  - moves the file to the staging state. It tracks the file

- `git commit -m message`
  - commit your code with a message

- First time
    -> create a repo in github
    -> follow the instructions displayed in github
        `git remote add origin https://github.com/ankit77raj/firstproject.git`
        `git branch -M main`
        `git push -u origin main`


https://github.com/ankit77raj/firstproject.git




















