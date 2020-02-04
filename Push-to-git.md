# How to Push to Github
1. Create a new repository on [Git Hub](https://www.github.com)

1. Open your terminal

1. Change your present working directory to the project you are working on

1. Initialize Git
```
git init
```
5. Add your files to git. This "stages" them
``` 
 git add .
 ```
6. Commit the files 
``` 
git commit -m " "
```
7. Get URL from Git Hub for your repository

1. Add the URL to your remote repository 
```
git remote add origin *URL HERE*
# Sets the new remote
git remote -v
# Verifies the new remote URL

```

9. Finally, push the changes to Git Hub
```
git push -u orgin master
# Pushes the changes in your local repository up to the remote repository you specified as the origin
```





