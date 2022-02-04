# Task 1.1 Git

The work began with git installation by typing command:
```
sudo apt-get install git
``` 
Then global configs were changed .
``` 
git config --global user.name "TarasSh15"
git config --global user.email tarassh15@gmail.com
git config --global core.editor "code --wait"
``` 
After new repo **DevOps_online_Ivano-Frankivsk_2022Q1Q2** was created it was cloned by command:
```
git clone https://github.com/TarasSh15/DevOps_online_Ivano-Frankivsk_2022Q1Q2.git
``` 
Then a new file readme.txt was created and commited.
```
touch readme.txt
git add readme.txt
git commit -m "Add readme.txt"
```
Then a new branch and file were created and commited.
```
git branch develop
git checkout develop
touch index.html
git add index.html
git commit
```
A new branch and folder with name "images" was created. 3 images were saved in folder and then commited with new folder.
```
git branch images
git checkout images
mkdir images
cd images/
```
When images were added
```
git add task1.1/
git commit
```
Added images to index.html and commited.

After switching to develop branch and creating a new one-style, a folder with file inside it was created and comitted too. Style folder with style source inside it were created and commited too. And **index.html** was edited by style file.

Switched to develop branch and merged 2 other branches into develop.
```
git checkout develop
git merge images
git merge style
```

After merging style the merge conflit has appeared. After resolving it in index.html second attempt to merge was executed and commited.
```
git add index.html
git commit -m "merge images and style"
```
Switched to main branch and merged it with develop branch. Next all changes with all branches were pushed to origin.
```
git checkout main
git merge develop
git push origin --all
```
## About DevOps

DevOps metodology was created by combining developer and operations specialisations. So DevOps is a specialist that knows development, quality assurance and technology operations. This specialist is involved in every stage of software development life style and all production depends on him.
