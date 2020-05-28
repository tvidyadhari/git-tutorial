# Git Tutorial
Learning git hands-on, newtonschool 

## Step 1: Clone a remote repo to local

```
git clone <remote-repo-url>
```
for ex: 
```
git clone https://github.com/tvidyadhari/git-tutorial.git
```

## Step 2: Enter cloned directory

```
cd <repo-name>
```
for ex:
```
cd git-tutorial
```

## Step 3: After saving file check git status

```
git status
```

## Step 4: Add modified file to stage

```
git add <file-name>
```
for ex:
```
git add readme.md
```

## Step 5: Commit your file so it is ready to be pushed to remote 
```
git commit -m "message"
```
for ex:
```
git commit -m "updated README.md file"
```

## Step 6: Push your file to remote repository
```
git push origin master
```
