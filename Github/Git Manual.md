git config --global user.name "name"  
git config --global user.email "mail"  


git init  
(git clone [url])  
git remote add origin https://github.com/Ambiyang/demo  
git push origin master  
git pull origin master  

git commit --amend -m "5 and 6"  

git reset HEAD --hard (reset rep,index,work)  
git reset HEAD --soft (reset rep)  
git reset HEAD (reset rep,index)  

git rebase -i HEAD~5  


team git

git pull --rebase  
git pull --continu  

git remote -v  
git remote add upstream url:id/rep  

#### ignore updating
git rm -r --cached .  
git add .  
git commit -m 'update .gitignore'  





