# Atividade Avaliativa - Git Colaborativo com Portugol

## Integrantes do grupo
- João Lemos Furlan
- Rafael Vioto Guimarães
## Objetivo
Desenvolver colaborativamente um algoritmo em Portugol de uma calculadora quie recebe 2 números e da a soma e o produto entre eles.

## Etapas realizadas por cada membro

### Rafael Guimarães
Eu criei o repositório e coloquei minha dupla como colaborador fiz a chave ssh e clonei o repositorio
crie a pasta de programação modifiquei colocando minha parte do código e dei git add git commit e git push meu parceiro fez a parte dele e também editei esse READ.ME

### João Lemos
 Eu fui adicionado ao repositorio logo apos isso, dei git clone e cd atividade-git-final para entrar no repositorio esperei minha dupla fazer a parte dele dei git pull e fiz minha parte do codigo dai dei git add git commit e git push e finalizamos a parte do portugol depois disso editei minha parte do READ.ME 

### Comandos de Rafael
compuni@maker258 MINGW64 ~
$ git config --global --unset user.name

compuni@maker258 MINGW64 ~
$ git config --global --unset user.email

compuni@maker258 MINGW64 ~
$ ls -al ~/.ssh
total 29
drwxr-xr-x 1 compuni 1049089    0 Apr  7 20:09 ./
drwxr-xr-x 1 compuni 1049089    0 Apr 14 19:25 ../
-rw-r--r-- 1 compuni 1049089 3401 Apr  7 20:03 id_rsa
-rw-r--r-- 1 compuni 1049089  756 Apr  7 20:03 id_rsa.pub
-rw-r--r-- 1 compuni 1049089  828 Apr  7 20:09 known_hosts
-rw-r--r-- 1 compuni 1049089   92 Apr  7 20:09 known_hosts.old

compuni@maker258 MINGW64 ~
$ rm -f ~/.ssh/id_rsa*

compuni@maker258 MINGW64 ~
$ git config --global user.name Rafael

compuni@maker258 MINGW64 ~
$ git config --global user.email rafaelvioto@edu.unifil.br

compuni@maker258 MINGW64 ~
$ ssh-keygen -t rsa -b 4096 -C rafaelvioto@edu.unifil.br
Generating public/private rsa key pair.
Enter file in which to save the key (/c/Users/compuni/.ssh/id_rsa):
Enter passphrase (empty for no passphrase):
Enter same passphrase again:
Your identification has been saved in /c/Users/compuni/.ssh/id_rsa
Your public key has been saved in /c/Users/compuni/.ssh/id_rsa.pub
The key fingerprint is:
SHA256:IMEOgHJpV3pPq5LwS2GtujFwZIN33GDWbYmRyjAQ09Y rafaelvioto@edu.unifil.br
The key's randomart image is:
+---[RSA 4096]----+
|*= +=oo= .       |
|ooX+E=+ +        |
|o+=B=.+..        |
| + o++ + .       |
|. o o . S        |
| o + + .         |
|  o * .          |
|   = o           |
|  o..            |
+----[SHA256]-----+

compuni@maker258 MINGW64 ~
$ eval "$(ssh-agent -s)"
Agent pid 1799

compuni@maker258 MINGW64 ~
$ ssh-add ~/.ssh/id_rsa
Identity added: /c/Users/compuni/.ssh/id_rsa (rafaelvioto@edu.unifil.br)

compuni@maker258 MINGW64 ~
$ clip < ~/.ssh/id_rsa.pub

compuni@maker258 MINGW64 ~
$ git clone git@github.com:lilze215/atividade-git-final.git
Cloning into 'atividade-git-final'...
remote: Enumerating objects: 6, done.
remote: Counting objects: 100% (6/6), done.
remote: Compressing objects: 100% (3/3), done.
remote: Total 6 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
Receiving objects: 100% (6/6), done.

compuni@maker258 MINGW64 ~
$ git pull
fatal: not a git repository (or any of the parent directories): .git

compuni@maker258 MINGW64 ~
$ git pull git@github.com:lilze215/atividade-git-final.git
fatal: not a git repository (or any of the parent directories): .git

compuni@maker258 MINGW64 ~
$ cd atividade-git-final

compuni@maker258 MINGW64 ~/atividade-git-final (main)
$ git pull
Already up to date.

compuni@maker258 MINGW64 ~/atividade-git-final (main)
$ code .

compuni@maker258 MINGW64 ~/atividade-git-final (main)
$ git add .

compuni@maker258 MINGW64 ~/atividade-git-final (main)
$ git commit -m Metade do código adicionado
error: pathspec 'do' did not match any file(s) known to git
error: pathspec 'código' did not match any file(s) known to git
error: pathspec 'adicionado' did not match any file(s) known to git

compuni@maker258 MINGW64 ~/atividade-git-final (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   algoritmo.por


compuni@maker258 MINGW64 ~/atividade-git-final (main)
$ git commit -m "Metade do código feito"
[main 1aba2da] Metade do código feito
 1 file changed, 9 insertions(+), 1 deletion(-)

compuni@maker258 MINGW64 ~/atividade-git-final (main)
$ git push
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 12 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 417 bytes | 417.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To github.com:lilze215/atividade-git-final.git
   b1bb86f..1aba2da  main -> main

compuni@maker258 MINGW64 ~/atividade-git-final (main)
$

### Comandos do João
compuni@maker273 MINGW64 ~
$ git config --global --unset user.name

compuni@maker273 MINGW64 ~
$ git config --global --unset user.email

compuni@maker273 MINGW64 ~
$ rm -f ~/.ssh/id_rsa*

compuni@maker273 MINGW64 ~
$ git config --global user.name joaolms

compuni@maker273 MINGW64 ~
$ git config --global user.email jlemosfurlan@edu.unifil.br

compuni@maker273 MINGW64 ~
$ ssh-keygen -t rsa -b 4096 -C "seuemail@example.com"
Generating public/private rsa key pair.
Enter file in which to save the key (/c/Users/compuni/.ssh/id_rsa):
Created directory '/c/Users/compuni/.ssh'.
Enter passphrase (empty for no passphrase):
Enter same passphrase again:
Your identification has been saved in /c/Users/compuni/.ssh/id_rsa
Your public key has been saved in /c/Users/compuni/.ssh/id_rsa.pub
The key fingerprint is:
SHA256:HI6fLf82oHqxLHGk2pOw/zoPVj+mddxpBpJTvdvpj3o seuemail@example.com
The key's randomart image is:
+---[RSA 4096]----+
|                 |
|             .   |
|        .   . .  |
|       +.. o   . |
|      .oS + . .  |
|    . ooo+.+ o +.|
|     =o=++*.o *..|
|    o.*.=* oooE. |
|     .+X+ .oo+..o|
+----[SHA256]-----+

compuni@maker273 MINGW64 ~
$ ssh-keygen -t rsa -b 4096 -C jlemosfurlan@edu.unifil.br
Generating public/private rsa key pair.
Enter file in which to save the key (/c/Users/compuni/.ssh/id_rsa):
/c/Users/compuni/.ssh/id_rsa already exists.
Overwrite (y/n)?

compuni@maker273 MINGW64 ~
$ y
bash: y: command not found

compuni@maker273 MINGW64 ~
$ rm -f ~/.ssh/id_rsa*

compuni@maker273 MINGW64 ~
$ ssh-keygen -t rsa -b 4096 -C jlemosfurlan@edu.unifil.br
Generating public/private rsa key pair.
Enter file in which to save the key (/c/Users/compuni/.ssh/id_rsa):
Enter passphrase (empty for no passphrase):
Enter same passphrase again:
Your identification has been saved in /c/Users/compuni/.ssh/id_rsa
Your public key has been saved in /c/Users/compuni/.ssh/id_rsa.pub
The key fingerprint is:
SHA256:WLwHm87RejkqBq2DbLxitaHTdBMzOYQPxjppy96jm/k jlemosfurlan@edu.unifil.br
The key's randomart image is:
+---[RSA 4096]----+
|  . .            |
|   = . .         |
|  + + . +        |
| =   B o *       |
|o o  .* S o      |
| o +.o.o + .     |
|.o*.+o. + +      |
|.=B=o o  o .     |
|.B*E.o ..        |
+----[SHA256]-----+

compuni@maker273 MINGW64 ~
$ eval "$(ssh-agent -s)"
Agent pid 790

compuni@maker273 MINGW64 ~
$ clip < ~/.ssh/id_rsa.pub

compuni@maker273 MINGW64 ~
$ git clone git@github.com:lilze215/Atividade_3.git
Cloning into 'Atividade_3'...
The authenticity of host 'github.com (20.201.28.151)' can't be established.
ED25519 key fingerprint is SHA256:+DiY3wvvV6TuJJhbpZisF/zLDA0zPMSvHdkr4UvCOqU.
This key is not known by any other names
Are you sure you want to continue connecting (yes/no/[fingerprint])? yes
Warning: Permanently added 'github.com' (ED25519) to the list of known hosts.
remote: Enumerating objects: 33, done.
remote: Counting objects: 100% (33/33), done.
remote: Compressing objects: 100% (29/29), done.
remote: Total 33 (delta 6), reused 0 (delta 0), pack-reused 0 (from 0)
Receiving objects: 100% (33/33), 12.23 KiB | 3.06 MiB/s, done.
Resolving deltas: 100% (6/6), done.

compuni@maker273 MINGW64 ~
$ git clone https://github.com/lilze215/atividade-git-final.git
Cloning into 'atividade-git-final'...
remote: Enumerating objects: 3, done.
remote: Counting objects: 100% (3/3), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
Receiving objects: 100% (3/3), done.

compuni@maker273 MINGW64 ~
$ cd repositorio
bash: cd: repositorio: No such file or directory

compuni@maker273 MINGW64 ~
$ cd atividade-git-final

compuni@maker273 MINGW64 ~/atividade-git-final (main)
$ git pull
remote: Enumerating objects: 4, done.
remote: Counting objects: 100% (4/4), done.
remote: Compressing objects: 100% (2/2), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
Unpacking objects: 100% (3/3), 945 bytes | 23.00 KiB/s, done.
From https://github.com/lilze215/atividade-git-final
   84383c2..b1bb86f  main       -> origin/main
Updating 84383c2..b1bb86f
Fast-forward
 algoritmo.por | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 algoritmo.por

compuni@maker273 MINGW64 ~/atividade-git-final (main)
$ git add .

compuni@maker273 MINGW64 ~/atividade-git-final (main)
$ git commit -m Metade do codigo adicionado
error: pathspec 'do' did not match any file(s) known to git
error: pathspec 'codigo' did not match any file(s) known to git
error: pathspec 'adicionado' did not match any file(s) known to git

compuni@maker273 MINGW64 ~/atividade-git-final (main)
$ git commit -m "Metade do codigo adicionado"
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean

compuni@maker273 MINGW64 ~/atividade-git-final (main)
$ git pull
Already up to date.

compuni@maker273 MINGW64 ~/atividade-git-final (main)
$ git add .

compuni@maker273 MINGW64 ~/atividade-git-final (main)
$ git commit -m Metade do codigo adicionado
error: pathspec 'do' did not match any file(s) known to git
error: pathspec 'codigo' did not match any file(s) known to git
error: pathspec 'adicionado' did not match any file(s) known to git

compuni@maker273 MINGW64 ~/atividade-git-final (main)
$ git push origin main
git push


git push origin main


compuni@maker273 MINGW64 ~/atividade-git-final (main)
$ git push
Everything up-to-date

compuni@maker273 MINGW64 ~/atividade-git-final (main)
$ git pull
Already up to date.

compuni@maker273 MINGW64 ~/atividade-git-final (main)
$ git pull
remote: Enumerating objects: 5, done.
remote: Counting objects: 100% (5/5), done.
remote: Compressing objects: 100% (3/3), done.
remote: Total 3 (delta 0), reused 3 (delta 0), pack-reused 0 (from 0)
Unpacking objects: 100% (3/3), 397 bytes | 10.00 KiB/s, done.
From https://github.com/lilze215/atividade-git-final
   b1bb86f..1aba2da  main       -> origin/main
Updating b1bb86f..1aba2da
Fast-forward
 algoritmo.por | 10 +++++++++-
 1 file changed, 9 insertions(+), 1 deletion(-)

compuni@maker273 MINGW64 ~/atividade-git-final (main)
$ code .

compuni@maker273 MINGW64 ~/atividade-git-final (main)
$ git add .

compuni@maker273 MINGW64 ~/atividade-git-final (main)
$ git commit -m "código completo"
[main 9b3df07] código completo
 1 file changed, 4 insertions(+), 2 deletions(-)

compuni@maker273 MINGW64 ~/atividade-git-final (main)
$ git push
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 12 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 475 bytes | 475.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/lilze215/atividade-git-final.git
   1aba2da..9b3df07  main -> main

compuni@maker273 MINGW64 ~/atividade-git-final (main)
$



## Observações
Cada etapa foi realizada por apenas um integrante por vez, respeitando a ordem de commits e a integridade do código.
