
#to change to code use
```
code
```


The default interactive shell is now zsh.
To update your account to use zsh, please run `chsh -s /bin/zsh`.
For more details, please visit https://support.apple.com/kb/HT208050.
bash-3.2$ git@github.com:efarre/Workshop.git
bash: git@github.com:efarre/Workshop.git: No such file or directory
bash-3.2$ git clone git@github.com:efarre/Workshop.git
Cloning into 'Workshop'...
The authenticity of host 'github.com (140.82.114.4)' can't be established.
ED25519 key fingerprint is SHA256:+DiY3wvvV6TuJJhbpZisF/zLDA0zPMSvHdkr4UvCOqU.
This key is not known by any other names.
Are you sure you want to continue connecting (yes/no/[fingerprint])? yes
Warning: Permanently added 'github.com' (ED25519) to the list of known hosts.
Enter passphrase for key '/Users/Eva/.ssh/id_ed25519': 
warning: You appear to have cloned an empty repository.
bash-3.2$ pwd
/Users/Eva
bash-3.2$ ls
Applications                            MapManData                              Sites
BestBlastpTable.sh                      Michigan State University               Workshop
CytoscapeConfiguration                  Movies                                  Zotero
Desktop                                 Music                                   igv
Documents                               OneDrive - Michigan State University    opt
Downloads                               PERL                                    run_all.sh
Dropbox                                 Pictures                                slivka
Library                                 Public                                  slivka-bio
bash-3.2$ cd Workshop
bash-3.2$ ls
README.md
bash-3.2$ git status
On branch main

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        .ipynb_checkpoints/
        README.md

nothing added to commit but untracked files present (use "git add" to track)
bash-3.2$ git status
On branch main

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        .ipynb_checkpoints/
        README.md

nothing added to commit but untracked files present (use "git add" to track)
bash-3.2$ nano
bash-3.2$ git status
On branch main

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        .gitignore
        README.md

nothing added to commit but untracked files present (use "git add" to track)
bash-3.2$ git add -A
bash-3.2$ git status
On branch main

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   .gitignore
        new file:   README.md

bash-3.2$ git commit -m 'Added code to README'
[main (root-commit) a40be1d] Added code to README
 Committer: Eva Farre <Eva@EMFAir-super-2.local>
Your name and email address were configured automatically based
on your username and hostname. Please check that they are accurate.
You can suppress this message by setting them explicitly. Run the
following command and follow the instructions in your editor to edit
your configuration file:

    git config --global --edit

After doing this, you may fix the identity used for this commit with:

    git commit --amend --reset-author

 2 files changed, 2 insertions(+)
 create mode 100644 .gitignore
 create mode 100644 README.md
bash-3.2$ git push
Enter passphrase for key '/Users/Eva/.ssh/id_ed25519': 
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (4/4), 293 bytes | 293.00 KiB/s, done.
Total 4 (delta 0), reused 0 (delta 0), pack-reused 0
To github.com:efarre/Workshop.git
 * [new branch]      main -> main
bash-3.2$ git status
On branch main
Your branch is up to date with 'origin/main'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   README.md

no changes added to commit (use "git add" and/or "git commit -a")
bash-3.2$ git config --global --edit
bash-3.2$ git status
On branch main
Your branch is up to date with 'origin/main'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   README.md

no changes added to commit (use "git add" and/or "git commit -a")
bash-3.2$ git add README.md 
bash-3.2$ git status
On branch main
Your branch is up to date with 'origin/main'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   README.md

bash-3.2$ git commit -m 'Add code to readme (for real!)'
[main c95fcaa] Add code to readme (for real!)
 1 file changed, 107 insertions(+), 1 deletion(-)
bash-3.2$ git push
Enter passphrase for key '/Users/Eva/.ssh/id_ed25519': 
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 8 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 1.57 KiB | 1.57 MiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To github.com:efarre/Workshop.git
   a40be1d..c95fcaa  main -> main
bash-3.2$ 