# SLUG
## GIT and OSD for Surrey LUG

### This was mainly copied from a DuckDuckGo search, like most commits to GIT.

sudo apt install git

> git clone git@github.com:drgnomage/SLUG.git

If you wish to submit changes to this repo, please email me your GitHub username so I can add you as a collaborator or make a pull request.



## Configuring your local GIT settings

git config --global user.name "[name]"

git config --global user.email "[email address]"

git config --global color.ui auto



## Creating or using a git repo

git init [project-name]

git clone [url]

git pull

git pull --rebase


## Updating a repo

git add [file or .] 

git commit -m "[descriptive message]"

git push [alias] [branch]

git push [alias] :[branch]


## Branching and merging

git branch

git branch [branch-name]

git checkout [branch-name]

git merge [branch]

git branch -d [branch-name]


## Stashing

git stash

git stash save [message]

git stash pop

git stash list

git stash show

git stash drop



## Repo maintenance

git rm [file]

git rm --cached [file]

git mv [file-original] [file-renamed]

git ls-files --other --ignored --exclude-standard

git revert -n <sha>



## Investigation

git log

git log --follow [file]

git status

git diff

git diff [first-branch]...[second-branch]

git show [commit]

git reset [commit]

git reset --hard [commit]

git fetch [bookmark] [branch]

git merge [bookmark]/[branch]
