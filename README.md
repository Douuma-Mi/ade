# ade
adeem
---------

a@DESKTOP-EU5P40C MINGW64 ~/Desktop/learn_git_again
$ git init
Initialized empty Git repository in C:/Users/a/Desktop/learn_git_again/.git/

a@DESKTOP-EU5P40C MINGW64 ~/Desktop/learn_git_again (master)
$ git add .

a@DESKTOP-EU5P40C MINGW64 ~/Desktop/learn_git_again (master)
$ git commit -m 'vide'
[master (root-commit) cf81f6d] vide
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 third.txt.txt

a@DESKTOP-EU5P40C MINGW64 ~/Desktop/learn_git_again (master)
$ git add third.txt
fatal: pathspec 'third.txt' did not match any files

a@DESKTOP-EU5P40C MINGW64 ~/Desktop/learn_git_again (master)
$ git commit -m "ajout de third.txt"
On branch master
nothing to commit, working tree clean

a@DESKTOP-EU5P40C MINGW64 ~/Desktop/learn_git_again (master)
$ git log
commit cf81f6d16f9e2129821a6c32a3151389fb80fdae (HEAD -> master)
Author: unknown <ademmathlouthi27705220@gmail.com>
Date:   Tue Jun 6 12:31:32 2023 +0100

    vide

a@DESKTOP-EU5P40C MINGW64 ~/Desktop/learn_git_again (master)
$ git add quatrième.txt
fatal: pathspec 'quatrième.txt' did not match any files

a@DESKTOP-EU5P40C MINGW64 ~/Desktop/learn_git_again (master)
$ git commit -m 'quatrième.txt'
On branch master
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        "quatri\303\250me.txt.txt"

nothing added to commit but untracked files present (use "git add" to track)

a@DESKTOP-EU5P40C MINGW64 ~/Desktop/learn_git_again (master)
$ git commit -m 'quatrième.txt'
On branch master
Changes not staged for commit:
  (use "git add/rm <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        deleted:    third.txt.txt

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        "quatri\303\250me.txt"
        third.txt

no changes added to commit (use "git add" and/or "git commit -a")

a@DESKTOP-EU5P40C MINGW64 ~/Desktop/learn_git_again (master)
$ git add quatrième.txt

a@DESKTOP-EU5P40C MINGW64 ~/Desktop/learn_git_again (master)
$ git commit -m 'quatrième.txt'
[master 19c76ff] quatrième.txt
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 "quatri\303\250me.txt"

a@DESKTOP-EU5P40C MINGW64 ~/Desktop/learn_git_again (master)
$ git rm --cached third.txt
fatal: pathspec 'third.txt' did not match any files

a@DESKTOP-EU5P40C MINGW64 ~/Desktop/learn_git_again (master)
$ git add third.txt

a@DESKTOP-EU5P40C MINGW64 ~/Desktop/learn_git_again (master)
$ git rm --cached third.txt
rm 'third.txt'

a@DESKTOP-EU5P40C MINGW64 ~/Desktop/learn_git_again (master)
$ git add third.txt
fatal: pathspec 'third.txt' did not match any files

a@DESKTOP-EU5P40C MINGW64 ~/Desktop/learn_git_again (master)
$ git add .

a@DESKTOP-EU5P40C MINGW64 ~/Desktop/learn_git_again (master)
$ git commit -m 'fassa5na'
[master 9e210b6] fassa5na
 1 file changed, 0 insertions(+), 0 deletions(-)
 delete mode 100644 third.txt.txt

a@DESKTOP-EU5P40C MINGW64 ~/Desktop/learn_git_again (master)
$ git log
commit 9e210b6239b466d9f2e55db17fbe919b743e7deb (HEAD -> master)
Author: unknown <ademmathlouthi27705220@gmail.com>
Date:   Tue Jun 6 12:48:13 2023 +0100

    fassa5na

commit 19c76ff2f2e17d4d6de3e1e5efae9b8a14c442a8
Author: unknown <ademmathlouthi27705220@gmail.com>
Date:   Tue Jun 6 12:42:35 2023 +0100

    quatrième.txt

commit cf81f6d16f9e2129821a6c32a3151389fb80fdae
Author: unknown <ademmathlouthi27705220@gmail.com>
Date:   Tue Jun 6 12:31:32 2023 +0100

    vide

a@DESKTOP-EU5P40C MINGW64 ~/Desktop/learn_git_again (master)
$ git config --global
usage: git config [<options>]

Config file location
    --global              use global config file
    --system              use system config file
    --local               use repository config file
    --worktree            use per-worktree config file
    -f, --file <file>     use given config file
    --blob <blob-id>      read config from given blob object

Action
    --get                 get value: name [value-pattern]
    --get-all             get all values: key [value-pattern]
    --get-regexp          get values for regexp: name-regex [value-pattern]
    --get-urlmatch        get value specific for the URL: section[.var] URL
    --replace-all         replace all matching variables: name value [value-patt
ern]
    --add                 add a new variable: name value
    --unset               remove a variable: name [value-pattern]
    --unset-all           remove all matches: name [value-pattern]
    --rename-section      rename section: old-name new-name
    --remove-section      remove a section: name
    -l, --list            list all
    --fixed-value         use string equality when comparing values to 'value-pa
ttern'
    -e, --edit            open an editor
    --get-color           find the color configured: slot [default]
    --get-colorbool       find the color setting: slot [stdout-is-tty]

Type
    -t, --type <type>     value is given this type
    --bool                value is "true" or "false"
    --int                 value is decimal number
    --bool-or-int         value is --bool or --int
    --bool-or-str         value is --bool or string
    --path                value is a path (file or directory name)
    --expiry-date         value is an expiry date

Other
    -z, --null            terminate values with NUL byte
    --name-only           show variable names only
    --includes            respect include directives on lookup
    --show-origin         show origin of config (file, standard input, blob, com
mand line)
    --show-scope          show scope of config (worktree, local, global, system,
 command)
    --default <value>     with --get, use default value when missing entry


a@DESKTOP-EU5P40C MINGW64 ~/Desktop/learn_git_again (master)
$
