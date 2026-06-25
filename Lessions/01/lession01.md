#A. Setup environment:
1. NMV (Node Version Manager)
- Engine
> brew install nvm
2. Node:
> nvm install v22.9.0
> nvm use v22.9.0

#B. Git config:
- Create new folder and init git:
> git init
- Config username: 
> git config --global user.name "Your-name"
- Config email
> git config --globlal user.email"your-email"
- Config branch
> git config --global init.defaultBranch main
- Connect to repo on Github
> git remote add origin <ssh_link>

> git add .


> git commit -m"init files"


> git push origin main

#C. Connect SSH and add to Github
- Create SSH key:
> ssh-keygen -t rsa -b 4096 -C "your_email@example.com"
- get ssh key:
> cat ~/.ssh/id_rsa.pub
- Then go to Github and add new SSH key in settings

#D. Install playwright
- Create new playwright folder
- Run:
> npm init playwright@latest
