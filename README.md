create project //but first, must generate SSH keys, private and public
0. create NEW repository on GitHub.com in your account
1. mkdir *NAME PROJECT* //make directory
2. cd *NAME PROJECT* //enter in it
3. git init //initializing our repositories
4. touch README.md //creating file
5. change README.md //write steps of making the project in it
6. git add --all //prepare all the project files for the commit
7. git commit -m "our cooment for this commit" //make commit with comment
8. git remote add origin *SSH path to repository
* // linking remote and local
9. git branch -m main //if you didn't rename before
10. git push -u origin main //first time do it with '-u rigin main', Next time just 'git push'
11. git remote -v //make sure to synchronize, the only difference is - fetch and push

