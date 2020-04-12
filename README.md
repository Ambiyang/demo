# README

git config --list

git config --global core.autocrlf true

git config --global core.safecrlf false



delete

1.git rm 1.txt

2.rm 1.txt

use 1 will add change to index automaticlly


add

1.git add .

add all

2.git add 1.txt 2.txt

add specific

3.git add -p a

partially add


diff

1.git diff

diff between work space and index

2.git diff --cached

diff between index and repository

3.git diff version/HEAD/tag

diff between work space and repository


commit

git commit -m "comment"

git commit -a -m "comment"

git commit -am "comment"

git commit

will let you write comment in vim

git commit --amend -m "comment"

merge the last with cur commit


git 分支不能直接push 要用 git push origin branchname

还有个git push -u origin branchname 用这个以后就可以直接git push了


git remote add origin https://github.com/Ambiyang/learning

git push origin master


fork流

1.fork

2.git clone self-url

3.git remote add upstream official-url 官方有更新自己可以同步

用git pull upstream master来同步















