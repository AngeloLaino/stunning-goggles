###How to create a new file local and push it to remote repo

##Open Git Bush

 * Go to your local repo

```sh
$ cd "local_repo"

 * Create a newfile.md

```sh
$ git touch newfile.md

 * Modify "newfile.md" with notepad (or similia) and save it

 * Check the status of your files

```sh
$ git status

 * Add the file to commit just one file newfile.md or all the changes with .

```sh
$ git add newfile.md

or

```sh
$ git add .

 * Commit for a change leaving a messagge (-m "") to describe the change

```sh
$ git commit -m "leave a message"

 * Push the file changed to your remote repo

```sh
$ git push remote master


