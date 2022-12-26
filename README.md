## g.abouali adds ##



# Creating a remote rep on github#

1.use add to creat a new rep.

2.give a name to the rep.

# Working with the created remote rep using VSC. #

creat a new folder (123) on desktop, open (123) on VSC, then follow these commands.
git init
git add README.md
git commit -m "first commit"
git branch -M master.
git remote add origin https://github.com/GAbouali/test-1.git
git push -u origin main

__how to push your changes from the local rep to the remote rep?__

git push : upload your changes to the remote rerp.

__how to pull your changes from the remote rep to the local rep?__

git pull : download your changes to the local rep.

__join to the work group on an existing remote repository.__


1.use the sent link.
2.fork the repository to creat your version of (adds and adjusments) on the project.
3.creat a new file on VSC, then follow the next commands.
* git clone (link of fork) : to connect the new file with the forked rep.
* cd (forked file name) : to change direction of your changes to  the remote rep space.
* git branch (family name) : creat a new branch where you will add and save your changes.
* git push -u (branch name) : to link our branch with the forked rep.
* git push : to upload your changes to the remote forked rep.
* send a pull request on the git hub, to send your changes to the rep admin to check your changes.