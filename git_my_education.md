# Guidelines

## Markdown

Italicized text is the *cat's meow*.

I just love **bold text**.

To create a list add asterix: 
* First item

To make a header just add # 
## Header

## Repositary setup and save changes

* To initiate repositary please enter *git init*

* to add the file in our future commit we enter *git add 'file name'*

* to create commit just enter *git commit -m 'comment'*

* to see log you enter *git log*

* to get back to your previous version you enter *git checkout 'number'*


## Check repositary

_Git status_ allows to see the status of indexed files in your directory and see untracked files.
To ignore files you have to create file .gitignore

## Cancel changes

To get to current status of the project you use _git main_ command.
You can also use _Git Revert_ or _Git Cancel_ for canceling undesired changes.
* to get back to your previous commit you just enter _git checkout and commit number_ (first 4-6 charachters are enough) like _git checkout 92a4_
## Summary

# How to work with remote repositary

* First you have to create an account at HitHub.com

* We can clone any remote reposoitary to your remote repositary with command **clone** and link to that repositary you want to clone

* Pay attention that you need to work in right directory and to switch to the right directory you use command **cd** and directory name

* to avoid adding your changes in master branch upon merge of repositary, please create separate branch

* to get your local repositary be available on GitHub, you have to open/create your local repositary, then you go to GitHub and create new repositary.

* next you choose from available options and copy commands you need. Like: **Git remote add origin [link]**, **git branch -M main**, **git push -u origin main**. 

* to get your changes done locally updated on remote repositary you have to use command **git push**

* if changes made on remote repositary and you'd like to get them on your local machine then you use command **git pull**
 