# This is git test for beginner

```bash
echo "" > xxx.txt
touch xxx.xxx
git init
git add . or specific
git status #about those files included or not
git restore --staged xxx.xxx
git commmit -a -m "somthing"
git commit -m "something"  --amend
git commit -m "I'm not sure about this"
git log
git diff
git restore xxx.xxx //after deleted
git log --online 

git rebash -i --root // something beyond

git branch newbranch
git branch
git switch xxbranch
git merge -m "what you wanna say" xxbranch
git branch -d xxbranch #delete the branch

#test2

git remote add origin git@github.com:yupose-martin/CPP.git
git push remote origin //这个哥们儿是真不懂
git pull
git config --global --list 
//to change it use "git config --global user.email or user.name....(this could be email or name)
git diff
/* some mistaked encountered

$ git push -u origin main
To github.com:yupose-martin/gittest.git
 ! [rejected]        main -> main (non-fast-forward)
error: failed to push some refs to 'github.com:yupose-martin/gittest.git'
hint: Updates were rejected because the tip of your current branch is behind
hint: its remote counterpart. Integrate the remote changes (e.g.
hint: 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.

```

