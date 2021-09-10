# Atividade_presncial_UC7

Colaborador 1:

CT WEB FULL STACK@ESN914D1235037 MINGW64 /g/SENAI/Atividade_presencial_UC7
$ git config --global user.name "Willian Bonfim"

CT WEB FULL STACK@ESN914D1235037 MINGW64 /g/SENAI/Atividade_presencial_UC7
$ git config --global user.email "willianhsb@gmail.com"

CT WEB FULL STACK@ESN914D1235037 MINGW64 /g/SENAI/Atividade_presencial_UC7
$ git init
Initialized empty Git repository in G:/SENAI/Atividade_presencial_UC7/.git/

CT WEB FULL STACK@ESN914D1235037 MINGW64 /g/SENAI/Atividade_presencial_UC7 (master)
$ git status
On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        index.txt

nothing added to commit but untracked files present (use "git add" to track)

CT WEB FULL STACK@ESN914D1235037 MINGW64 /g/SENAI/Atividade_presencial_UC7 (master)
$ git add .

CT WEB FULL STACK@ESN914D1235037 MINGW64 /g/SENAI/Atividade_presencial_UC7 (master)
$ git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   index.txt


CT WEB FULL STACK@ESN914D1235037 MINGW64 /g/SENAI/Atividade_presencial_UC7 (master)
$ git commit -m "Iniciando Projeto Colaborador "
[master (root-commit) 5f45aa0] Iniciando Projeto Colaborador
 1 file changed, 1 insertion(+)
 create mode 100644 index.txt

CT WEB FULL STACK@ESN914D1235037 MINGW64 /g/SENAI/Atividade_presencial_UC7 (master)
$ git remote add origin https://github.com/willianhsb/Atividade_presncial_UC7.git

CT WEB FULL STACK@ESN914D1235037 MINGW64 /g/SENAI/Atividade_presencial_UC7 (master)
$ git branck -M main
git: 'branck' is not a git command. See 'git --help'.

The most similar command is
        branch

CT WEB FULL STACK@ESN914D1235037 MINGW64 /g/SENAI/Atividade_presencial_UC7 (master)
$ git branch -M main

CT WEB FULL STACK@ESN914D1235037 MINGW64 /g/SENAI/Atividade_presencial_UC7 (main)
$ git push -u origin main
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Writing objects: 100% (3/3), 252 bytes | 252.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/willianhsb/Atividade_presncial_UC7.git
 * [new branch]      main -> main
Branch 'main' set up to track remote branch 'main' from 'origin'.

CT WEB FULL STACK@ESN914D1235037 MINGW64 /g/SENAI/Atividade_presencial_UC7 (main)
$
-------------------------------------------------------------------------
  Colaborador 2:
  
CT WEB FULL STACK@ESN914D1235036 MINGW64 ~/Desktop/Projeto colaborador turma B/Atividade_presncial_UC7 (main)
$ git config
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
    --replace-all         replace all matching variables: name value [value-pattern]
    --add                 add a new variable: name value
    --unset               remove a variable: name [value-pattern]
    --unset-all           remove all matches: name [value-pattern]
    --rename-section      rename section: old-name new-name
    --remove-section      remove a section: name
    -l, --list            list all
    --fixed-value         use string equality when comparing values to 'value-pattern'
    -e, --edit            open an editor
    --get-color           find the color configured: slot [default]
    --get-colorbool       find the color setting: slot [stdout-is-tty]

Type
    -t, --type <>         value is given this type
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
    --show-origin         show origin of config (file, standard input, blob, command line)
    --show-scope          show scope of config (worktree, local, global, system, command)
    --default <value>     with --get, use default value when missing entry


CT WEB FULL STACK@ESN914D1235036 MINGW64 ~/Desktop/Projeto colaborador turma B/Atividade_presncial_UC7 (main)
$ The requested URL returned error: 403
bash: The: command not found

CT WEB FULL STACK@ESN914D1235036 MINGW64 ~/Desktop/Projeto colaborador turma B/Atividade_presncial_UC7 (main)
$ git config --global user.name "sheldon fernando"

CT WEB FULL STACK@ESN914D1235036 MINGW64 ~/Desktop/Projeto colaborador turma B/Atividade_presncial_UC7 (main)
$ git config --global user.email "sheldon.guimaraes@hotmail.com"

CT WEB FULL STACK@ESN914D1235036 MINGW64 ~/Desktop/Projeto colaborador turma B/Atividade_presncial_UC7 (main)
$ git push origin main
remote: Permission to willianhsb/Atividade_presncial_UC7.git denied to sheldonfernando.
fatal: unable to access 'https://github.com/willianhsb/Atividade_presncial_UC7.git/': The requested URL returned error: 403

CT WEB FULL STACK@ESN914D1235036 MINGW64 ~/Desktop/Projeto colaborador turma B/Atividade_presncial_UC7 (main)
$ git push origin main
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 6 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 336 bytes | 168.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/willianhsb/Atividade_presncial_UC7.git
   83c8dec..ad7c038  main -> main

CT WEB FULL STACK@ESN914D1235036 MINGW64 ~/Desktop/Projeto colaborador turma B/Atividade_presncial_UC7 (main)
