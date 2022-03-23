## how to create a new repository locally, then push to remote host

First set up git in the local folder:
```
git init
```

Add/edit files, then do the usual:
```
git add .
git commit -m "Message"
```

In order to push this to github, you'll need to create a new empty repository with the same name in github. Then:
```
git remote add origin git@github.com:username/new-empty-repository.git
git remote -v # shows you the remote repositories you are connected to
git push origin main # might need to use master instead of main
```