# git-tricks

Here i will put some tricks which i use to save time in analyzing repository

### List remote branches ordered by last commit date with date, commit hash, author and all this colorized:

`git for-each-ref --sort=-committerdate refs/remotes/origin --format='%(HEAD)%(color:yellow)%(refname:short)|%(color:bold green)%(committerdate:relative)|%(color:blue)%(subject)|%(color:magenta)%(authorname)%(color:reset)'|column -ts'|'`

