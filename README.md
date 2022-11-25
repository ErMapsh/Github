![image](https://www.freecodecamp.org/news/content/images/2022/07/git-github.png)

##### Note: If you want to quickly work with Git Technology, then this is for you. In this video we gonna learn basic thing of git Technology that us to push data on github and pull a data from git repository

# Git: 
- Git is a distributed version control system (DVCS) for tracking changes to files

#### Step: To complete following step you should have github account, if you haven't, just go  and create

1. Installation of git on user/programmer system
2. Configuration of git and github (SSH Key)
3. learn how to clone repository, how to push, how to pull

- [Official Site of github (for help)](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent)

# lets move forward
## 1.Installation of Git
- [Download git](https://git-scm.com/downloads)


## 2.Configuration of git and github
1. Open GitBash

2. Paste the text below, substituting in your GitHub email address.
```ssh-keygen -t ed25519 -C "your_email@example.com"```

3. Adding your SSH key to the ssh-agent
```eval "$(ssh-agent -s)"```

4. Add your SSH private key to the ssh-agent.
```ssh-add ~/.ssh/id_ed25519```

5. generating the SSH key here, Copy the SSH public key to your clipboard.
``` tail ~/.ssh/id_ed25519.pub```

6. Go to github ---> Setting---> SSH and GPG keys --> ssh key 
and new SSH Key, Paste the generated ssh key that u copied.

7. use clear cmd/ open new git bash 
- git config --global user.name "FIRST_NAME LAST_NAME"

- ```git config --global user.name "Yourname"```
- ```git config --global user.email "Youremail@gmail.com"```

# 🎉Congratulation, you complete most important task here. 

## 3.Commands that gonna we use
0. git status --> status of directory
1. git init -> to make git repository
2. git add . --> adding all file to staging area
3. git commit -m  "message" --> we commiting here 
4. git push --> pushing data to github
5. git pull --> to pull update
6. rm -rf .git --> to make non git repository
7. git log --> git commit history
8. git clone --> clone the git repo

## Git Information
![Git checkup](https://intellipaat.com/blog/wp-content/uploads/2020/04/Git-1-1.jpg)</br>

![Git arch](https://intellipaat.com/blog/wp-content/uploads/2020/04/Git-3.jpg)</br>
![Git arch](https://intellipaat.com/blog/wp-content/uploads/2020/04/Git-4.jpg)</br>

Note: there is lots of things in git but I'm gonna show you important cmds thats help you make github repository
