'git init' : initialize current folder as git repository
'git clone <URL>' :brings the git repo from <URL> to current folder 
'git status' : tells us what we need to about our repository and its state 
'git add <FILE>': adds <FILE> to the staging area 
'git commit' : open a text editor to write commit message 
'git commit -m "MESSAGE"' : writes MESSAGE as a commit without a text editor 
'git log': shows the log (history) of our commits 
	'git log --oneline': shows the shorter oneline commit
'git diff': compare current uncommited state with last known git state 
	'git diff --staged': runs git diff between the staging area and last known state 
'git diff HEAD~<NUMBER>':compares HEAD with commit <NUMBER> ago (relative)
'git digg <HASH>': compares HEAD with the commit in <HASH>
