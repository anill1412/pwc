
PG208_42+CVR@pg208_42 MINGW64 ~/Desktop/New folder (main)
$ git init
Reinitialized existing Git repository in C:/Users/CVR/Desktop/New folder/.git/

PG208_42+CVR@pg208_42 MINGW64 ~/Desktop/New folder (main)
$ git config --global user.name "anill1412"

PG208_42+CVR@pg208_42 MINGW64 ~/Desktop/New folder (main)
$ git config --global user.email "anilkumarsipurusetty@gmail.com"

PG208_42+CVR@pg208_42 MINGW64 ~/Desktop/New folder (main)
$ git config --global --list
user.name=anill1412
user.email=anilkumarsipurusetty@gmail.com

PG208_42+CVR@pg208_42 MINGW64 ~/Desktop/New folder (main)
$ git init
Reinitialized existing Git repository in C:/Users/CVR/Desktop/New folder/.git/

PG208_42+CVR@pg208_42 MINGW64 ~/Desktop/New folder (main)
$ git clone https://github.com/anill1412/pwc.git
Cloning into 'pwc'...
remote: Enumerating objects: 3, done.
remote: Counting objects: 100% (3/3), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
Receiving objects: 100% (3/3), done.

PG208_42+CVR@pg208_42 MINGW64 ~/Desktop/New folder (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        pwc/

nothing added to commit but untracked files present (use "git add" to track)

PG208_42+CVR@pg208_42 MINGW64 ~/Desktop/New folder (main)
$ ls
file1  pwc/

PG208_42+CVR@pg208_42 MINGW64 ~/Desktop/New folder (main)
$ cd pwc

PG208_42+CVR@pg208_42 MINGW64 ~/Desktop/New folder/pwc (main)
$ ls
README.md

PG208_42+CVR@pg208_42 MINGW64 ~/Desktop/New folder/pwc (main)
$ ^C

PG208_42+CVR@pg208_42 MINGW64 ~/Desktop/New folder/pwc (main)
$ vi README.md

PG208_42+CVR@pg208_42 MINGW64 ~/Desktop/New folder/pwc (main)
$ git init
Reinitialized existing Git repository in C:/Users/CVR/Desktop/New folder/pwc/.git/

PG208_42+CVR@pg208_42 MINGW64 ~/Desktop/New folder/pwc (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   README.md

no changes added to commit (use "git add" and/or "git commit -a")

PG208_42+CVR@pg208_42 MINGW64 ~/Desktop/New folder/pwc (main)
$ git add .
warning: in the working copy of 'README.md', LF will be replaced by CRLF the next time Git touches it

PG208_42+CVR@pg208_42 MINGW64 ~/Desktop/New folder/pwc (main)
$ git config -m "modified readme file"
error: unknown switch `m'
usage: git config [<options>]

Config file location
    --[no-]global         use global config file
    --[no-]system         use system config file
    --[no-]local          use repository config file
    --[no-]worktree       use per-worktree config file
    -f, --[no-]file <file>
                          use given config file
    --[no-]blob <blob-id> read config from given blob object

Action
    --[no-]get            get value: name [value-pattern]
    --[no-]get-all        get all values: key [value-pattern]
    --[no-]get-regexp     get values for regexp: name-regex [value-pattern]
    --[no-]get-urlmatch   get value specific for the URL: section[.var] URL
    --[no-]replace-all    replace all matching variables: name value [value-pattern]
    --[no-]add            add a new variable: name value
    --[no-]unset          remove a variable: name [value-pattern]
    --[no-]unset-all      remove all matches: name [value-pattern]
    --[no-]rename-section rename section: old-name new-name
    --[no-]remove-section remove a section: name
    -l, --[no-]list       list all
    --[no-]fixed-value    use string equality when comparing values to 'value-pattern'
    -e, --[no-]edit       open an editor
    --[no-]get-color      find the color configured: slot [default]
    --[no-]get-colorbool  find the color setting: slot [stdout-is-tty]

Type
    -t, --[no-]type <type>
                          value is given this type
    --bool                value is "true" or "false"
    --int                 value is decimal number
    --bool-or-int         value is --bool or --int
    --bool-or-str         value is --bool or string
    --path                value is a path (file or directory name)
    --expiry-date         value is an expiry date

Other
    -z, --[no-]null       terminate values with NUL byte
    --[no-]name-only      show variable names only
    --[no-]includes       respect include directives on lookup
    --[no-]show-origin    show origin of config (file, standard input, blob, command line)
    --[no-]show-scope     show scope of config (worktree, local, global, system, command)
    --[no-]default <value>
                          with --get, use default value when missing entry
    --[no-]comment <value>
                          human-readable comment string (# will be prepended as needed)


PG208_42+CVR@pg208_42 MINGW64 ~/Desktop/New folder/pwc (main)
$ git commit -m "modified readme file"
[main c0d7e39] modified readme file
 1 file changed, 2 insertions(+), 1 deletion(-)

PG208_42+CVR@pg208_42 MINGW64 ~/Desktop/New folder/pwc (main)
$ git status
On branch main
Your branch is ahead of 'origin/main' by 1 commit.
  (use "git push" to publish your local commits)

nothing to commit, working tree clean

PG208_42+CVR@pg208_42 MINGW64 ~/Desktop/New folder/pwc (main)
$ git branch -M main

PG208_42+CVR@pg208_42 MINGW64 ~/Desktop/New folder/pwc (main)
$ git remote add origin https://github.com/anill1412/pwc.git
error: remote origin already exists.

PG208_42+CVR@pg208_42 MINGW64 ~/Desktop/New folder/pwc (main)
$ git push -u origin main
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Writing objects: 100% (3/3), 282 bytes | 282.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/anill1412/pwc.git
   ee743c4..c0d7e39  main -> main
branch 'main' set up to track 'origin/main'.

PG208_42+CVR@pg208_42 MINGW64 ~/Desktop/New folder/pwc (main)
$ git log
commit c0d7e39c65ce212f17f1115123e0b03aef255937 (HEAD -> main, origin/main, origin/HEAD)
Author: anill1412 <anilkumarsipurusetty@gmail.com>
Date:   Wed May 15 16:30:23 2024 +0530

    modified readme file

commit ee743c46f34f0073b26d763e2878072f36aa0c32
Author: anill1412 <121108329+anill1412@users.noreply.github.com>
Date:   Tue May 14 17:29:18 2024 +0530

    Initial commit

PG208_42+CVR@pg208_42 MINGW64 ~/Desktop/New folder/pwc (main)
$ git log --oneline
c0d7e39 (HEAD -> main, origin/main, origin/HEAD) modified readme file
ee743c4 Initial commit

PG208_42+CVR@pg208_42 MINGW64 ~/Desktop/New folder/pwc (main)
$ git branch
* main

PG208_42+CVR@pg208_42 MINGW64 ~/Desktop/New folder/pwc (main)
$ git branch service

PG208_42+CVR@pg208_42 MINGW64 ~/Desktop/New folder/pwc (main)
$ git branch
* main
  service

PG208_42+CVR@pg208_42 MINGW64 ~/Desktop/New folder/pwc (main)
$ git checkout service
Switched to branch 'service'

PG208_42+CVR@pg208_42 MINGW64 ~/Desktop/New folder/pwc (service)
$ ls
README.md

PG208_42+CVR@pg208_42 MINGW64 ~/Desktop/New folder/pwc (service)
$ vi file2

PG208_42+CVR@pg208_42 MINGW64 ~/Desktop/New folder/pwc (service)
$ git status
On branch service
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        file2

nothing added to commit but untracked files present (use "git add" to track)

PG208_42+CVR@pg208_42 MINGW64 ~/Desktop/New folder/pwc (service)
$ git add .
warning: in the working copy of 'file2', LF will be replaced by CRLF the next time Git touches it

PG208_42+CVR@pg208_42 MINGW64 ~/Desktop/New folder/pwc (service)
$ git commit -m "f2 is created"
[service 8a06db5] f2 is created
 1 file changed, 1 insertion(+)
 create mode 100644 file2

PG208_42+CVR@pg208_42 MINGW64 ~/Desktop/New folder/pwc (service)
$ git log --oneline
8a06db5 (HEAD -> service) f2 is created
c0d7e39 (origin/main, origin/HEAD, main) modified readme file
ee743c4 Initial commit

PG208_42+CVR@pg208_42 MINGW64 ~/Desktop/New folder/pwc (service)
$ git push -u origin main
Everything up-to-date
branch 'main' set up to track 'origin/main'.

PG208_42+CVR@pg208_42 MINGW64 ~/Desktop/New folder/pwc (service)
$ git push -u origin service
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 297 bytes | 297.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
remote:
remote: Create a pull request for 'service' on GitHub by visiting:
remote:      https://github.com/anill1412/pwc/pull/new/service
remote:
To https://github.com/anill1412/pwc.git
 * [new branch]      service -> service
branch 'service' set up to track 'origin/service'.

PG208_42+CVR@pg208_42 MINGW64 ~/Desktop/New folder/pwc (service)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

PG208_42+CVR@pg208_42 MINGW64 ~/Desktop/New folder/pwc (main)
$ git log --oneline
c0d7e39 (HEAD -> main, origin/main, origin/HEAD) modified readme file
ee743c4 Initial commit

PG208_42+CVR@pg208_42 MINGW64 ~/Desktop/New folder/pwc (main)
$ git merge service
Updating c0d7e39..8a06db5
Fast-forward
 file2 | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 file2

PG208_42+CVR@pg208_42 MINGW64 ~/Desktop/New folder/pwc (main)
$ git log --oneline
8a06db5 (HEAD -> main, origin/service, service) f2 is created
c0d7e39 (origin/main, origin/HEAD) modified readme file
ee743c4 Initial commit

PG208_42+CVR@pg208_42 MINGW64 ~/Desktop/New folder/pwc (main)
$ git push -u origin main
Total 0 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/anill1412/pwc.git
   c0d7e39..8a06db5  main -> main
branch 'main' set up to track 'origin/main'.

PG208_42+CVR@pg208_42 MINGW64 ~/Desktop/New folder/pwc (main)
$
