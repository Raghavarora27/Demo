1. git init
2. git remote add origin https://github.com/usernam/reponame.git
(Link local and Cloud repo---)
3. git pull origin master -----> to fetch all repo files on cloud 
4. git add .
5. git status
6. git commit -m"message"
7. git push origin master
8. git brannch branchname --> making a new branch
9. git branch -> check current branch
10. git checkout branchname --> change branch
11. git checkout -b feature1 --> 9 and 10 step both
12. git branch -d feature1 --> delete branch locally
12. git merge branchname 
13. git push origin --delete feature1 --> delete cloud branch
14. To remove commit -- two ways - 1. hard deletion 2. soft deletion
14. git reset --hard HEAD~1 ----> deletes the top commit
14. git reset --soft HEAD~1 ----> deletes the top commit(but code not reset)