AIML@mitm-aiml-008 MINGW64 ~
$ cd desktop

AIML@mitm-aiml-008 MINGW64 ~/desktop
$ cd MIT_AI-ML
bash: cd: MIT_AI-ML: No such file or directory

AIML@mitm-aiml-008 MINGW64 ~/desktop
$ cd MIT_AI-ML

AIML@mitm-aiml-008 MINGW64 ~/desktop/MIT_AI-ML
$ GIT INIT
git: 'INIT' is not a git command. See 'git --help'.

AIML@mitm-aiml-008 MINGW64 ~/desktop/MIT_AI-ML
$

AIML@mitm-aiml-008 MINGW64 ~/desktop/MIT_AI-ML
$ git init
Initialized empty Git repository in C:/Users/AIML/Desktop/MIT_AI-ML/.git/

AIML@mitm-aiml-008 MINGW64 ~/desktop/MIT_AI-ML (master)
$ mkdir README.md


AIML@mitm-aiml-008 MINGW64 ~/desktop/MIT_AI-ML (master)
$

AIML@mitm-aiml-008 MINGW64 ~/desktop/MIT_AI-ML (master)
$ mkdir devops_notes.txt

AIML@mitm-aiml-008 MINGW64 ~/desktop/MIT_AI-ML (master)
$ git add
Nothing specified, nothing added.
hint: Maybe you wanted to say 'git add .'?
hint: Disable this message with "git config set advice.addEmptyPathspec false"

AIML@mitm-aiml-008 MINGW64 ~/desktop/MIT_AI-ML (master)
$ git add .

AIML@mitm-aiml-008 MINGW64 ~/desktop/MIT_AI-ML (master)
$ git commit -m "initial commit"
Author identity unknown

*** Please tell me who you are.

Run

  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"

to set your account's default identity.
Omit --global to set the identity only in this repository.

fatal: unable to auto-detect email address (got 'AIML@mitm-aiml-008.(none)')

AIML@mitm-aiml-008 MINGW64 ~/desktop/MIT_AI-ML (master)
$  git config --global user.email "beulahyam2006@gmail.com.com"

AIML@mitm-aiml-008 MINGW64 ~/desktop/MIT_AI-ML (master)
$  git config --global user.email "beulahyam2006@gmail.com"

AIML@mitm-aiml-008 MINGW64 ~/desktop/MIT_AI-ML (master)
$ LS
README.md  devops_notes.txt

AIML@mitm-aiml-008 MINGW64 ~/desktop/MIT_AI-ML (master)
$ git branch -M main

AIML@mitm-aiml-008 MINGW64 ~/desktop/MIT_AI-ML (main)
$ git remote add origin https://github.com/BEULAHDEVA/MIT_AI-ML.git

AIML@mitm-aiml-008 MINGW64 ~/desktop/MIT_AI-ML (main)
$ git push -u origin main
error: src refspec main does not match any
error: failed to push some refs to 'https://github.com/BEULAHDEVA/MIT_AI-ML.git'

AIML@mitm-aiml-008 MINGW64 ~/desktop/MIT_AI-ML (main)
$
[200~git add .
bash: [200~git: command not found

AIML@mitm-aiml-008 MINGW64 ~/desktop/MIT_AI-ML (main)
$ git commit -m "Initial commit"
On branch main

Initial commit

nothing to commit (create/copy files and use "git add" to track)

AIML@mitm-aiml-008 MINGW64 ~/desktop/MIT_AI-ML (main)
$ git push -u origin main
error: src refspec main does not match any
error: failed to push some refs to 'https://github.com/BEULAHDEVA/MIT_AI-ML.git'

AIML@mitm-aiml-008 MINGW64 ~/desktop/MIT_AI-ML (main)
$ git add .

AIML@mitm-aiml-008 MINGW64 ~/desktop/MIT_AI-ML (main)
$ ^[[200~git add .
bash: $'\E[200~git': command not found

AIML@mitm-aiml-008 MINGW64 ~/desktop/MIT_AI-ML (main)
$ git commit -m "Initial commit"
On branch main

Initial commit

nothing to commit (create/copy files and use "git add" to track)

AIML@mitm-aiml-008 MINGW64 ~/desktop/MIT_AI-ML (main)
$ git push -u origin main
error: src refspec main does not match any
error: failed to push some refs to 'https://github.com/BEULAHDEVA/MIT_AI-ML.git'

AIML@mitm-aiml-008 MINGW64 ~/desktop/MIT_AI-ML (main)
$ git log.
git: 'log.' is not a git command. See 'git --help'.

The most similar command is
        log

AIML@mitm-aiml-008 MINGW64 ~/desktop/MIT_AI-ML (main)
$

AIML@mitm-aiml-008 MINGW64 ~/desktop/MIT_AI-ML (main)
$ log
bash: log: command not found

AIML@mitm-aiml-008 MINGW64 ~/desktop/MIT_AI-ML (main)
$      log
bash: log: command not found

AIML@mitm-aiml-008 MINGW64 ~/desktop/MIT_AI-ML (main)
$ git log
fatal: your current branch 'main' does not have any commits yet

AIML@mitm-aiml-008 MINGW64 ~/desktop/MIT_AI-ML (main)
$ git branch -M main
git push -u origin main
error: src refspec main does not match any
error: failed to push some refs to 'https://github.com/BEULAHDEVA/MIT_AI-ML.git'

AIML@mitm-aiml-008 MINGW64 ~/desktop/MIT_AI-ML (main)
$ git show-ref

AIML@mitm-aiml-008 MINGW64 ~/desktop/MIT_AI-ML (main)
$ git add .

AIML@mitm-aiml-008 MINGW64 ~/desktop/MIT_AI-ML (main)
$ git commit -m "initial commit"
On branch main

Initial commit

nothing to commit (create/copy files and use "git add" to track)

AIML@mitm-aiml-008 MINGW64 ~/desktop/MIT_AI-ML (main)
$ ls
README.md/  devops_notes.txt/

AIML@mitm-aiml-008 MINGW64 ~/desktop/MIT_AI-ML (main)
$ git add README.md

AIML@mitm-aiml-008 MINGW64 ~/desktop/MIT_AI-ML (main)
$ git commit -m "first commit"
On branch main

Initial commit

nothing to commit (create/copy files and use "git add" to track)

AIML@mitm-aiml-008 MINGW64 ~/desktop/MIT_AI-ML (main)
$ ls
README.md/  devops_notes.txt/

AIML@mitm-aiml-008 MINGW64 ~/desktop/MIT_AI-ML (main)
$ ^[[200~# This creates a file named README.md (replacing the folder if it's empty)
bash: syntax error near unexpected token `('
# This creates a text file
echo "Notes for DevOps" > devops_notes.txt

AIML@mitm-aiml-008 MINGW64 ~/desktop/MIT_AI-ML (main)
$ echo "# MIT AI-ML" > README.md
bash: README.md: Is a directory

AIML@mitm-aiml-008 MINGW64 ~/desktop/MIT_AI-ML (main)
$

AIML@mitm-aiml-008 MINGW64 ~/desktop/MIT_AI-ML (main)
$ # This creates a text file

AIML@mitm-aiml-008 MINGW64 ~/desktop/MIT_AI-ML (main)
$ echo "Notes for DevOps" > devops_notes.txt
bash: devops_notes.txt: Is a directory

AIML@mitm-aiml-008 MINGW64 ~/desktop/MIT_AI-ML (main)
$ rm -rf README.md/ devops_notes.txt/

AIML@mitm-aiml-008 MINGW64 ~/desktop/MIT_AI-ML (main)
$

AIML@mitm-aiml-008 MINGW64 ~/desktop/MIT_AI-ML (main)
$ ls

AIML@mitm-aiml-008 MINGW64 ~/desktop/MIT_AI-ML (main)
$ touch README.md devops_notes.txt

AIML@mitm-aiml-008 MINGW64 ~/desktop/MIT_AI-ML (main)
$ ls -F
README.md  devops_notes.txt

AIML@mitm-aiml-008 MINGW64 ~/desktop/MIT_AI-ML (main)
$ git add .
git commit -m "Convert folders to files and initial commit"
git push -u origin main
[main (root-commit) d57f4ab] Convert folders to files and initial commit
 2 files changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 README.md
 create mode 100644 devops_notes.txt
info: please complete authentication in your browser...
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 20 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 254 bytes | 254.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/BEULAHDEVA/MIT_AI-ML.git
 * [new branch]      main -> main
branch 'main' set up to track 'origin/main'.

AIML@mitm-aiml-008 MINGW64 ~/desktop/MIT_AI-ML (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean

AIML@mitm-aiml-008 MINGW64 ~/desktop/MIT_AI-ML (main)
$

AIML@mitm-aiml-008 MINGW64 ~/desktop/MIT_AI-ML (main)
$ git commit -m "message text"
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean

AIML@mitm-aiml-008 MINGW64 ~/desktop/MIT_AI-ML (main)
$ echo "This is the first line of my README" > README.md

AIML@mitm-aiml-008 MINGW64 ~/desktop/MIT_AI-ML (main)
$ echo "This is a new line of notes" >> devops_notes.txt

AIML@mitm-aiml-008 MINGW64 ~/desktop/MIT_AI-ML (main)
$

AIML@mitm-aiml-008 MINGW64 ~/desktop/MIT_AI-ML (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   README.md
        modified:   devops_notes.txt

no changes added to commit (use "git add" and/or "git commit -a")

AIML@mitm-aiml-008 MINGW64 ~/desktop/MIT_AI-ML (main)
$ git add .
warning: in the working copy of 'README.md', LF will be replaced by CRLF the next time Git touches it
warning: in the working copy of 'devops_notes.txt', LF will be replaced by CRLF the next time Git touches it

AIML@mitm-aiml-008 MINGW64 ~/desktop/MIT_AI-ML (main)
$ git commit -m "message text"
[main d22d0a8] message text
 2 files changed, 2 insertions(+)

AIML@mitm-aiml-008 MINGW64 ~/desktop/MIT_AI-ML (main)
$ git push
Enumerating objects: 7, done.
Counting objects: 100% (6/6), done.
Delta compression using up to 20 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (4/4), 356 bytes | 356.00 KiB/s, done.
Total 4 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/BEULAHDEVA/MIT_AI-ML.git
   d57f4ab..d22d0a8  main -> main

AIML@mitm-aiml-008 MINGW64 ~/desktop/MIT_AI-ML (main)
$

AIML@mitm-aiml-008 MINGW64 ~/desktop/MIT_AI-ML (main)
$
This is the first line of my README
