/*This is just to learn about git hub commands

//This has all the commans that were used for future references

test@test-PC MINGW64 ~/Desktop/Fundamentals of Git
$ touch index.html

test@test-PC MINGW64 ~/Desktop/Fundamentals of Git
$ touch  app.js

test@test-PC MINGW64 ~/Desktop/Fundamentals of Git
$ git init
Initialized empty Git repository in C:/Users/test/Desktop/Fundamentals of Git/.git/

test@test-PC MINGW64 ~/Desktop/Fundamentals of Git (master)
$ git config --global user.name 'Hardik Sheth'

test@test-PC MINGW64 ~/Desktop/Fundamentals of Git (master)
$ git config --global user.email 'hps0003@uah.edu'

test@test-PC MINGW64 ~/Desktop/Fundamentals of Git (master)
$ git add index.html

test@test-PC MINGW64 ~/Desktop/Fundamentals of Git (master)
$ git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)

        new file:   index.html

Untracked files:
  (use "git add <file>..." to include in what will be committed)

        app.js


test@test-PC MINGW64 ~/Desktop/Fundamentals of Git (master)
$ git rm --cashed index.html
error: unknown option `cashed'
usage: git rm [<options>] [--] <file>...

    -n, --dry-run         dry run
    -q, --quiet           do not list removed files
    --cached              only remove from the index
    -f, --force           override the up-to-date check
    -r                    allow recursive removal
    --ignore-unmatch      exit with a zero status even if nothing matched


test@test-PC MINGW64 ~/Desktop/Fundamentals of Git (master)
$ git rm --cached index.html
rm 'index.html'

test@test-PC MINGW64 ~/Desktop/Fundamentals of Git (master)
$ git status
On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)

        app.js
        index.html

nothing added to commit but untracked files present (use "git add" to track)

test@test-PC MINGW64 ~/Desktop/Fundamentals of Git (master)
$ git add *.html

test@test-PC MINGW64 ~/Desktop/Fundamentals of Git (master)
$ git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)

        new file:   index.html

Untracked files:
  (use "git add <file>..." to include in what will be committed)

        app.js


test@test-PC MINGW64 ~/Desktop/Fundamentals of Git (master)
$ git rm --cached index.html
rm 'index.html'

test@test-PC MINGW64 ~/Desktop/Fundamentals of Git (master)
$ git add .

test@test-PC MINGW64 ~/Desktop/Fundamentals of Git (master)
$ git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)

        new file:   app.js
        new file:   index.html


test@test-PC MINGW64 ~/Desktop/Fundamentals of Git (master)
$ git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)

        new file:   app.js
        new file:   index.html

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git checkout -- <file>..." to discard changes in working directory)

        modified:   index.html


test@test-PC MINGW64 ~/Desktop/Fundamentals of Git (master)
$ git add .

test@test-PC MINGW64 ~/Desktop/Fundamentals of Git (master)
$ git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)

        new file:   app.js
        new file:   index.html


test@test-PC MINGW64 ~/Desktop/Fundamentals of Git (master)
$ git commit
[master (root-commit) bc6ad35]  Initial commit
 2 files changed, 8 insertions(+)
 create mode 100644 app.js
 create mode 100644 index.html

test@test-PC MINGW64 ~/Desktop/Fundamentals of Git (master)
$ git status
On branch master
nothing to commit, working tree clean

test@test-PC MINGW64 ~/Desktop/Fundamentals of Git (master)
$ git status
On branch master
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git checkout -- <file>..." to discard changes in working directory)

        modified:   app.js

no changes added to commit (use "git add" and/or "git commit -a")

test@test-PC MINGW64 ~/Desktop/Fundamentals of Git (master)
$ git add .

test@test-PC MINGW64 ~/Desktop/Fundamentals of Git (master)
$ git commit -m 'changed app.js'
[master d05dd1f] changed app.js
 1 file changed, 1 insertion(+)

test@test-PC MINGW64 ~/Desktop/Fundamentals of Git (master)
$ touch .gitignore

test@test-PC MINGW64 ~/Desktop/Fundamentals of Git (master)
$ touch log.txt

test@test-PC MINGW64 ~/Desktop/Fundamentals of Git (master)
$ git add .

test@test-PC MINGW64 ~/Desktop/Fundamentals of Git (master)
$ git status
On branch master
Changes to be committed:
  (use "git reset HEAD <file>..." to unstage)

        new file:   .gitignore


test@test-PC MINGW64 ~/Desktop/Fundamentals of Git (master)
$ git add.
git: 'add.' is not a git command. See 'git --help'.

The most similar command is
        add

test@test-PC MINGW64 ~/Desktop/Fundamentals of Git (master)
$ git add .

test@test-PC MINGW64 ~/Desktop/Fundamentals of Git (master)
$ git status
On branch master
Changes to be committed:
  (use "git reset HEAD <file>..." to unstage)

        new file:   .gitignore
        new file:   dir1/app1.js


test@test-PC MINGW64 ~/Desktop/Fundamentals of Git (master)
$ git branch login

test@test-PC MINGW64 ~/Desktop/Fundamentals of Git (master)
$ get status
bash: get: command not found

test@test-PC MINGW64 ~/Desktop/Fundamentals of Git (master)
$ git status
On branch master
Changes to be committed:
  (use "git reset HEAD <file>..." to unstage)

        new file:   .gitignore
        new file:   dir1/app1.js


test@test-PC MINGW64 ~/Desktop/Fundamentals of Git (master)
$ get commit -m 'another change'
bash: get: command not found

test@test-PC MINGW64 ~/Desktop/Fundamentals of Git (master)
$ git commmit -m 'another change'
git: 'commmit' is not a git command. See 'git --help'.

The most similar command is
        commit

test@test-PC MINGW64 ~/Desktop/Fundamentals of Git (master)
$ git commit -m 'another change'
[master 5531bc5] another change
 2 files changed, 3 insertions(+)
 create mode 100644 .gitignore
 create mode 100644 dir1/app1.js

test@test-PC MINGW64 ~/Desktop/Fundamentals of Git (master)
$ git checkout

test@test-PC MINGW64 ~/Desktop/Fundamentals of Git (master)
$ git checkout login
Switched to branch 'login'

test@test-PC MINGW64 ~/Desktop/Fundamentals of Git (login)
$ touch login.html

test@test-PC MINGW64 ~/Desktop/Fundamentals of Git (login)
$ git commit -m 'login form'
On branch login
Changes not staged for commit:
        modified:   index.html

Untracked files:
        .gitignore
        dir1/
        login.html

no changes added to commit

test@test-PC MINGW64 ~/Desktop/Fundamentals of Git (login)
$ git commit -m 'login form'
On branch login
Changes not staged for commit:
        modified:   index.html

Untracked files:
        .gitignore
        dir1/
        dir2/
        log.txt
        login.html

no changes added to commit

test@test-PC MINGW64 ~/Desktop/Fundamentals of Git (login)
$ git add.
git: 'add.' is not a git command. See 'git --help'.

The most similar command is
        add

test@test-PC MINGW64 ~/Desktop/Fundamentals of Git (login)
$ git commit -m 'login form'
On branch login
Changes not staged for commit:
        modified:   index.html

Untracked files:
        .gitignore
        dir1/
        dir2/
        log.txt
        login.html

no changes added to commit

test@test-PC MINGW64 ~/Desktop/Fundamentals of Git (login)
$ git checkout login
Already on 'login'
M       index.html

test@test-PC MINGW64 ~/Desktop/Fundamentals of Git (login)
$ git add.
git: 'add.' is not a git command. See 'git --help'.

The most similar command is
        add

test@test-PC MINGW64 ~/Desktop/Fundamentals of Git (login)
$ git add .

test@test-PC MINGW64 ~/Desktop/Fundamentals of Git (login)
$ git commit -m
error: switch `m' requires a value
usage: git commit [<options>] [--] <pathspec>...

    -q, --quiet           suppress summary after successful commit
    -v, --verbose         show diff in commit message template

Commit message options
    -F, --file <file>     read message from file
    --author <author>     override author for commit
    --date <date>         override date for commit
    -m, --message <message>
                          commit message
    -c, --reedit-message <commit>
                          reuse and edit message from specified commit
    -C, --reuse-message <commit>
                          reuse message from specified commit
    --fixup <commit>      use autosquash formatted message to fixup specified commit
    --squash <commit>     use autosquash formatted message to squash specified commit
    --reset-author        the commit is authored by me now (used with -C/-c/--amend)
    -s, --signoff         add Signed-off-by:
    -t, --template <file>
                          use specified template file
    -e, --edit            force edit of commit
    --cleanup <default>   how to strip spaces and #comments from message
    --status              include status in commit message template
    -S, --gpg-sign[=<key-id>]
                          GPG sign commit

Commit contents options
    -a, --all             commit all changed files
    -i, --include         add specified files to index for commit
    --interactive         interactively add files
    -p, --patch           interactively add changes
    -o, --only            commit only specified files
    -n, --no-verify       bypass pre-commit and commit-msg hooks
    --dry-run             show what would be committed
    --short               show status concisely
    --branch              show branch information
    --porcelain           machine-readable output
    --long                show status in long format (default)
    -z, --null            terminate entries with NUL
    --amend               amend previous commit
    --no-post-rewrite     bypass post-rewrite hook
    -u, --untracked-files[=<mode>]
                          show untracked files, optional modes: all, normal, no. (Default: all)


test@test-PC MINGW64 ~/Desktop/Fundamentals of Git (login)
$ git commit -m 'login form'
[login 2a9d58c] login form
 6 files changed, 7 insertions(+)
 create mode 100644 .gitignore
 create mode 100644 dir1/app1.js
 create mode 100644 dir2/app2.js
 create mode 100644 log.txt
 create mode 100644 login.html

test@test-PC MINGW64 ~/Desktop/Fundamentals of Git (login)
$ git checkout master
Switched to branch 'master'

test@test-PC MINGW64 ~/Desktop/Fundamentals of Git (master)
$ git merge login
Auto-merging .gitignore
CONFLICT (add/add): Merge conflict in .gitignore
Automatic merge failed; fix conflicts and then commit the result.

test@test-PC MINGW64 ~/Desktop/Fundamentals of Git (master|MERGING)
$ git merge login
error: Merging is not possible because you have unmerged files.
hint: Fix them up in the work tree, and then use 'git add/rm <file>'
hint: as appropriate to mark resolution and make a commit.
fatal: Exiting because of an unresolved conflict.

test@test-PC MINGW64 ~/Desktop/Fundamentals of Git (master|MERGING)
$ git remotr
git: 'remotr' is not a git command. See 'git --help'.

The most similar command is
        remote

test@test-PC MINGW64 ~/Desktop/Fundamentals of Git (master|MERGING)
$ git remote

test@test-PC MINGW64 ~/Desktop/Fundamentals of Git (master|MERGING)
$ git remote add origin https://github.com/hardiksheth12/github.git

test@test-PC MINGW64 ~/Desktop/Fundamentals of Git (master|MERGING)
$ git remote
origin

test@test-PC MINGW64 ~/Desktop/Fundamentals of Git (master|MERGING)
$ git push -u origin master
Counting objects: 12, done.
Delta compression using up to 2 threads.
Compressing objects: 100% (7/7), done.
Writing objects: 100% (12/12), 983 bytes | 89.00 KiB/s, done.
Total 12 (delta 0), reused 0 (delta 0)
To https://github.com/hardiksheth12/github.git
 * [new branch]      master -> master
Branch 'master' set up to track remote branch 'master' from 'origin'.

test@test-PC MINGW64 ~/Desktop/Fundamentals of Git (master|MERGING)
$ touch README.md

test@test-PC MINGW64 ~/Desktop/Fundamentals of Git (master|MERGING)
$ ^C

test@test-PC MINGW64 ~/Desktop/Fundamentals of Git (master|MERGING)
$*/
