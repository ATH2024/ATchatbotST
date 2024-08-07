
athabti@LAPTOP-SP3IG056 MINGW64 ~
$ ^[[200~
bash: $'\E[200~': command not found

athabti@LAPTOP-SP3IG056 MINGW64 ~
$ ls ~/.ssh/
id_ed25519_ATGITHUB  id_ed25519_ATGITHUB.pub

athabti@LAPTOP-SP3IG056 MINGW64 ~
$ ssh-add ~/.ssh/id_ed25519~^C

athabti@LAPTOP-SP3IG056 MINGW64 ~
$ ssh-add~/.id_ed25519_ATGITHUB
bash: ssh-add~/.id_ed25519_ATGITHUB: No such file or directory

athabti@LAPTOP-SP3IG056 MINGW64 ~
$ ^C

athabti@LAPTOP-SP3IG056 MINGW64 ~
$ ssh-add ~/.id_ed25519_ATGITHUB
Could not open a connection to your authentication agent.

athabti@LAPTOP-SP3IG056 MINGW64 ~
$ eval "$(ssh-agent -s)"
Agent pid 1224

athabti@LAPTOP-SP3IG056 MINGW64 ~
$ ssh-add ~/.id_ed25519_ATGITHUB
/c/Users/athabti/.id_ed25519_ATGITHUB: No such file or directory

athabti@LAPTOP-SP3IG056 MINGW64 ~
$ ssh-add ~/id_ed25519_ATGITHUB
/c/Users/athabti/id_ed25519_ATGITHUB: No such file or directory

athabti@LAPTOP-SP3IG056 MINGW64 ~
$ ssh-add c:\utilisateurs\athabti\.ssh\id_ed25519_ATGITHUB
c:utilisateursathabti.sshid_ed25519_ATGITHUB: No such file or directory

athabti@LAPTOP-SP3IG056 MINGW64 ~
$ ssh-add "/c/Users/athabti/.ssh/id_ed25519_ATGITHUB"
Identity added: /c/Users/athabti/.ssh/id_ed25519_ATGITHUB (athabti@free.fr)

athabti@LAPTOP-SP3IG056 MINGW64 ~
$ clip < ~/.ssh/id_ed25519_ATGITHUB.pub

athabti@LAPTOP-SP3IG056 MINGW64 ~
$  clip < ~/.ssh/id_ed25519_ATGITHUB.pub

athabti@LAPTOP-SP3IG056 MINGW64 ~
$ ls -al ~/.ssh
total 34
drwxr-xr-x 1 athabti 197121   0 Aug 21  2023 ./
drwxr-xr-x 1 athabti 197121   0 Aug  7 09:40 ../
-rw-r--r-- 1 athabti 197121 411 Aug 21  2023 id_ed25519_ATGITHUB
-rw-r--r-- 1 athabti 197121  97 Aug 21  2023 id_ed25519_ATGITHUB.pub
