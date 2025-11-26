# How to make a repository and upload it to github
* use `git init` to initialize a local repo
* use `git add` to add files to staging area where you can review changes between the new and the older version
* use `git commit -m 'any message'` to take a new snapshot in the repo history
create a new remote repo on github and use `git remote add` to add a new remote to fetch and push using either the https or ssh protocol and give a shortname like origin
use `git push` to upstram your repo history and if you are working in a team it is preferable to use `git pull` first to fetch and merge any updates, if you are on a new branch use the option u to upstream the branch first and then create a pull request on github


