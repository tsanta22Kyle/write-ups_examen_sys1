 write-ups_examen_sys1
* objectif : trouver les mot de passe
### level 0:
* commandes utilisées: pwd,cd,cat,ls
  - pwd : afficher le répertoire de travail
  - cd : changer le répertoire de travail
  - cat : lire un fichier
  - ls : afficher le contenu du répertoire courant
* Ma démarche :
  - j'ai changé de répertoire avec : cd /home/level/00_welcome/
  - puis ls
  - cat README.md
   - dans le fichier README.md: 
 ```
  Welcome to the WarChall box
  We hope you will learn a bit about linux systems here, and enjoy your st

================================
= All your activity is logged. =
================================
= If you find a way around our protections,
= please contact us!  =
= support@wechall.net =
=======================
We are looking for bitwarriors that can provide funny and educative chal
=======================

Oh .... and your solution to level0 is: "bitwarrior" without the quotes.

 - The WarChall Staff

  ```
### level 1 :
* commandes utilisées : cd,cat
* Ma démarche :
    -je suis allé dans le répertoire /home/level/01_choice_tree
  ```
  cd /home/level/01_choice_tree 
  ```
    -j'ai lu le fichier README.md (c'était inutile) 
  ```
  cat README.md
  ```
    -je suis allé dans blue/hats/white
  ```
  cd blue/hats/white
  cat README.EXE
  ```
   -j'ai découvert l'indice "GRAYHAT"
  ```
  BROTHER, TRUST ME
  THE WHITEHAT HAS NO SECRETS
  DEEP IN YOUR HEART YOU SHOULD BECOME A GRAYHAT
  ALWAYS KEEP A JOKER.

   - giz

  ```
   -je suis allé dans /home/level/01_choice_tree/blue/hats/grey/solution/patience/
  ```
  cd  /home/level/01_choice_tree/blue/hats/grey/solution/patience/
  cat SOLUTION.txt
  ```
  la solution est **patience**
  ### level 2 :
  * commandes utilisées : cd, cat, ls -al
      - ls -al : afficher le contenu du répertoire de façon détaillée 
  * Ma démarche :
      -je suis allé dans le répertoire du niveau
    ```
     cd /home/level/02/
     ls
    documents photos
    ```
    - je suis allé dans documents `cd documents`
    - lu  le fichier `cat letter.txt`
    ```
    Hey Jerry, I have sent you a letter.

    Greetings
        level02
      ```
     - je suis allé dans le répertoire photos `cd photos/` puis j'ai lu le fichier ` cat thumbnails`
      ```
      Super OS Thumbs v8.0
      Nothing here yet

      ```
      - il n'y avait rien , alors je suis retourné dans /home/level/02/
      - j'ai fait `ls -al ` pour afficher les fichiers cachés
        ```
        drwxr-xr-x  5 root level02 4096 Jan 11  2023 .
        drwxr-xr-x 19 root root    4096 Feb 11  2023 ..
        drwxr-xr-x  2 root level02 4096 Jan 11  2023 .porb
        drwxr-xr-x  2 root level02 4096 Jan 10  2023 documents
        drwxr-xr-x  2 root level02 4096 Jan 11  2023 photos
        ```
        - je suis allé dans .porb `cd .porb/` puis lu le fichier dedans `cat .solution`
          ```
          The solution is HiddenIsConfig
          ```
### level 3 : 
  * commandes utilisées : cd, cat, ls -al
  * Ma démarche:
      -  je me suis déplacé dans le répertoire du niveau `cd /home/level/03/`
      - `ls -al `
        ```
        total 16
        drwxrwxr-x  3 root    level03 4096 Jan 11  2023 .
        drwxr-xr-x 19 root    root    4096 Feb 11  2023 ..
        -rw-r--r--  1 level03 level03  122 Jan 11  2023 .bash_history
        drwxr-xr-x  3 level03 level03 4096 Jan 11  2023 .local
        ```
        - je suis allé dans .local/share/ `cd .local/share/`
          ```
          -bash: cd: .local/share/: Permission denied
          ```
        - je suis donc retourné dans level/03/ et j'ai lu l'autre fichier
          ` cat .bash_history`
 ```
          The solution to SSH3 is: RepeatingHistory
ls
whoami
exit
ls
ls -asl
nano .bash_history
ls -asl
cat .bash_history
ls -asl

```

### level 4 :
