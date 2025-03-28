<h1>To-Do List</h1><br>
This is my project to make a basic To-Do List. This project can help you complete your tasks on time and help you remembring which tasks are to be done before a specific time.<br>
<h3>How to add new tasks:</h3><br>
In the "tasks" add your task that you have to do and add the date by which you want to complete it and set a remainder for the due date if you want to.<br> 
<h3>Potential feature</h3><br>
This is a simple and user friendly project.<br>
By using it, you can increase your productivity because if you have the due date infront of you, you will do the task more efficiently adn quickly.<br>
It will reduce the behaviour of procastination.<br><br>
<h3>Steps to resolve conflicts:</h3><br>
You can simply open an advance text editor or IDE and there would be an option to resolve conflict by removing one cange or another or by adding the both changes.
But if you are using CLI(terminal) for merging and resolving conflicts, follow these steps:-<br>
1. merge the branches and you will see a warning i.e. conflict.<br>
2. open the file in text editor like nano, vim etc.<br>
There you will se some characters like: (>>>>>>> or MAIN) above the conflicted lines. You can simply remove the deired lines below these that you don't want to be in repo, if you wanna keep both, you can just remove the characters and save the file.<br>

<h1>Submission:-</h1><br>
<h3>Content of .gitignore: *.tmp 
*.log
build/
</h3><br>
<h3>Explaination of Task 2:</h3><br>
1. Created a new branch named "add-list-feature" using git branch "name" or git checkout -b "name".<br>
2. Switch to that branch using git checkout "name" (if you created using git checkout -b "name",you will already be in this branch).<br>
3. Created a text file named tasks.txt using touch command.<br>
4. Added sample in this file using a text editor named kate and saved it.<br>
5. Added and commit the changes using git add and git commit commands.<br>
6. switched back to main branch and merged add-list-feature branch using git merge command.<br>
<h3> Explaination of Tast 3:</h3><br>
1. Create a new remote repo in GitHub.<br>
2. Copy it's https: link and go to your local repo using cd command.<br>
3. use git init commad to initialise this local repo and use git remote add origin "link of remote repo" to make this local repo a git repo.<br>
4. Push this local repo to GitHub using git push command.<br>
5. If there are changes in a file directly in GitHub, you can pull that changes to local repo using git pull command.<br>
<h3> Explaination of Task 4:</h3><br>
1. create .gitinit file using touch command and open it in a text editor.<br>
2. add file extensions like *.tmp,*.log in to so that your git add and commit commands can ignore temporary and log files.<br>
3. Do required changes in README.md and if someone else also done changes in the README.md , resolve conflicts after git merge.(steps are mentioned above).<br>
4. After redolving conflicts, commit changes and push this to GitHub.
