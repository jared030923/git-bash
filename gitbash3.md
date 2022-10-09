### Commands
```sh
# First-time setup
$ git config --global user.name "(name)"
$ git config --global user.email (email address @ gachon.ac.kr)
$ git config --global init.defaultBranch main
$ git config --list
$ git config --list --show-origin

$ git init
$ git status
$ git all[file_name]
$ nano words.txt(file_name)
$ git add .
$ git rm --cached [file_name]
$ nano .gitignore
$ git commit -m "commit message"
```

#### $ git init
Initializing a Repository in an Existing Directory

#### $ git status
Checking Repository Status

#### $ git all[file_name]
Adding a new file to be staged (tracked)
You can use **$ nano words.txt(file_name)** to edit file

#### $ git add .
Adding all files to be staged (tracked)

#### $ git rm --cached [file_name]
Unstaging a file

#### $ nano .gitignore
Ignoring a file

###### *.a
 ignore all .a files
###### !lib.a
 but do track lib.a, even though you're ignoring /a files above
###### /TODO
 only ignore the TODO file in the current directory, not subdir/TODO
###### build/
 ignore all files in any directory named build
###### doc/*.txt
 ignore doc/notes.txt, but not doc/server/arch.txt
###### dox/**/*.pdf
 ignore all .pdf files in the doc/ directory and any of its subdirectories

#### $ git commit -m "commit message"
Commit files
