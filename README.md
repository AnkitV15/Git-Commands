# Git CheatSheet

```bash


 1) git init -- to initialize a repo
 2) git clone <repository link> -- to clone an existing repository
 3) git add filename(for single file) or .(dot) or (*) (for all files) -- to track a untracked file
 4) git status -- tracks an untracked file use (git status -s or git status --short ) -- for shorter description
 5) .gitignore -- to ignore untracked files
 6) git commit -- commit final/changed files permanently (git commit -m "message") -- another way to commit changes
 7) git log -- shows history of commited (git log -p -2) -- shows last two commit
 8) git commit --amend -- to commit any forget file without creating any new commit.(replacing the original one)
 9) git restore --staged filename --  to unstage a file into working directory
 10) git restore filename -- return to a previous version of a commited file
 11) git remote -- lists the remote servers configured generally origin (git remote -v) shows the URL of repository pointed by origin
 12) git remote add shortname url -- add new shortname to remote git repository
 13) git remote add shortname url -- add remote repository with git init
 14) git pull -- automatically update changes in local repository from central repository
 15) git remote rename oldname newname -- change remote name of url
 16) git remote remove remotename -- remove remote name
 17) git remote show origin -- shows a detailed information of remote reference
 18) git branch -- lists the branch
 19) git branch branchname -- creates a branch
 20) git checkout branchname -- moves to a new branch
 21) git checkout -b branchname -- creates and moves to a new branch
 22) git push remotename branchname -- push to central repository to branch
 23) git stash save -- to save an incomplete work but don't want to commit (note: the file must be tracked or should be in staging area
 24) git stash list -- lists the stash files
 25) git stash apply -- to get the stash files back and get working on those incomplete changes (note: if would only get back the first stash file)
 26) git stash apply stashname -- get the exact stash files
 27) git stash pop -- similar to git stash apply only difference is pop drops the file record from stash list and apply doesn't
 28) git stash show -- show difference between file changes
 29) git stash show stashname -- shows differences between exact files
 30) git stash drop -- deletes the latest stash or the most recent one ( you can also delete the specific one with stashname ) placed the name infront of command
 31) git stash clear -- clears the all stash files
 32) git tag -- lists the tagsnin alphabetical order
 33) git push origin tagname -- push tags to remote reference
 34) git push origin  --tags -- this would push all the tags
 35) git tag -d tagname -- delete a tag from local repository
 36) git push origin --delete tagname -- delete a tag from remote repository
 37) git merge branchname -- merges the branch specified into current branch and maintains a history of that branch
 38) git rebase branchname -- merges the branch with current branch without keeping commit history
 39) git pull --rebase origin main -- tells which file is causing merge conflict in local repository
 40) git mergetool -- manually conflicts is solved using this cmd
 41) git rebase --continue -- enter this command after mergetool to continue with changes done
 42) git rm --cached -r 'filename' -- this command removes current commit
 43) git branch -d branchname -- deletes a local branch
 44) git branch -D branchname -- if not updated/ not fully merged, still you want to delete
 45) git branch -r -- list all remote repository
 46) git push origin --delete branchname -- delete a remote branch 
 
 ```
