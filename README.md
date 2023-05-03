# **Git and Github**

Following the Fireship git tutorial

## **1. Basics init**
```git init```
To create a git repository

## **2. Basics status**
```git status```
To track changes in the repo

## **3. Basics .gitignore**
```.gitignore```
To ignore certain files to stop adding into the repo

## **4. Basics add**
```git add .``` adds all the files to staging

```git add {file_name}``` to add a specific file

## **5. Basics commint**
To have a log of commited files or take a snapshot
```git commint -m "{commit_message}"```

To commit without and add files to staging at the same time is done by
```git commint -a -m "{commit_message}"```

## **6. Git Remote**
To to config the git repo to the remote
```git remote add origin {repo_url}```
will add the remote url to the local repo

## **7. Git Push**
```git push origin master```
will push the local repo code the remote repo
