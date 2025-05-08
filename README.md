Notes: 

Your identification has been saved in /Users/Eva/.ssh/id_ed25519
Your public key has been saved in /Users/Eva/.ssh/id_ed25519.pub
The key fingerprint is:
SHA256:n03zf74hzsgDIU8ahS0tLQSQgrWkIqzCh9PNqYj5PHw farre@msu.edu
The key's randomart image is:
+--[ED25519 256]--+
|..o.o.o.=        |
|o+ o   = =       |
|+.o     =        |
|= o o .o o       |
|o+ o +  S . o    |
|o.+ .  . + + o   |
|oo .      + .... |
| oo E     ..+ ..o|
|  oo       o.o o=|
+----[SHA256]-----+

(base) EMFAir-super-2:~ Eva$ cat ~/.ssh/id_ed25519.pub
ssh-ed25519 AAAAC3NzaC1lZDI1NTE5AAAAIKwx9pVAjzgfVE164zJMIxOU3NIqfkwDO5nDRuPwHlij farre@msu.edu



IN new terminal

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

    
    ```  #this will be used as code ```
    git add -A
    ```
    
bash-3.2$ git status
On branch main

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   .gitignore
        new file:   README.md

bash-3.2$ 

# never do git add * do git add -A