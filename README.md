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
```git commit -m "{commit_message}"```

To commit without and add files to staging at the same time is done by
```git commit -a -m "{commit_message}"```

## **6. Git Remote**
To to config the git repo to the remote
```git remote add origin {repo_url}```
will add the remote url to the local repo

## **7. Git Push**
```git push origin master```
will push the local repo code the remote repo

## **8. Fetch and Merge**
```git fetch``` will download the file in memory

```git merge origin/master``` will merge local files with remote

## **9. Pull**
```git pull origin master``` will fetch and merge at the same time

```git pull``` is enough when the ```-u``` flag is added in when it is commited

## **10. Clone**
```git clone {repo_url} {folder_name}``` will clone a repo to local directory
