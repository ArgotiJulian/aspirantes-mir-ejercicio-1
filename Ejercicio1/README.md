PS C:\Users\Julian Argoti> ls

Directorio: C:\Users\Julian Argoti

Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
d-----        11/03/2023     14:21                .idlerc
d-----        11/03/2023     13:56                .ipython
d-----        04/01/2023     12:00                .ms-ad
d-----        06/05/2023     21:42                .ssh
d-----        11/03/2023     13:29                .vscode
d-----        06/05/2023     21:22                .vscode-cli
d-r---        04/01/2023     11:44                3D Objects
d-r---        04/01/2023     11:44                Contacts
d-----        05/05/2023     18:41                Desktop
d-----        21/02/2023     22:09                Documents
d-r---        10/05/2023     17:41                Downloads
d-r---        04/01/2023     11:44                Favorites
d-----        14/03/2023     11:23                HCWebControlService
d-r---        04/01/2023     11:44                Links
d-r---        04/01/2023     11:44                Music
d-r---        07/01/2023     12:02                OneDrive
dar--l        10/05/2023     17:40                OneDrive - 901139754_RISK MANAGEMENT SOLUTION COLOM
d-r---        04/01/2023     11:44                Saved Games
d-r---        04/01/2023     11:48                Searches
d-r---        06/01/2023     14:11                Videos
d-----        04/01/2023     11:48                Web
d-----        30/03/2023     11:47                WebComponents
-a----        05/05/2023     20:02           1184 .bash_history
-a----        05/05/2023     18:53             67 .gitconfig
-a----        08/05/2023     19:51             20 .lesshst
-a----        29/04/2023      9:24             15 advanced_ip_scanner_Aliases.bin
-a----        29/04/2023      9:24             15 advanced_ip_scanner_Comments.bin
-a----        29/04/2023      9:24            980 advanced_ip_scanner_MAC.bin

PS C:\Users\Julian Argoti> cd .\Desktop\

PS C:\Users\Julian Argoti\Desktop> md ejercicios


    Directorio: C:\Users\Julian Argoti\Desktop


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
d-----        10/05/2023     18:08                ejercicios

PS C:\Users\Julian Argoti\Desktop> cd .\ejercicios

Julian Argoti@PT-BOGSES-7002 MINGW64 ~
$ git config --global user.name
Julian Argoti

Julian Argoti@PT-BOGSES-7002 MINGW64 ~
$ git config --global user.email "julian_argoti_27@hotmail.com"

Julian Argoti@PT-BOGSES-7002 MINGW64 ~
$ git config --global user.email
julian_argoti_27@hotmail.com

Julian Argoti@PT-BOGSES-7002 MINGW64 ~/desktop/ejercicios
$ git init
Initialized empty Git repository in C:/Users/Julian Argoti/Desktop/ejercicios/.git/

Julian Argoti@PT-BOGSES-7002 MINGW64 ~/desktop/ejercicios (master)
$ ls -al
total 8
drwxr-xr-x 1 Julian Argoti 197121 0 May  5 18:56 ./
drwxr-xr-x 1 Julian Argoti 197121 0 May  5 18:41 ../
drwxr-xr-x 1 Julian Argoti 197121 0 May  5 18:56 .git/
drwxr-xr-x 1 Julian Argoti 197121 0 May  5 18:47 Ejercicio1/

Julian Argoti@PT-BOGSES-7002 MINGW64 ~/desktop/ejercicios (master)
$ git add .

Julian Argoti@PT-BOGSES-7002 MINGW64 ~/desktop/ejercicios (master)
$ git commit -m 'Versión Inicial'
[master (root-commit) ed50667] Versión Inicial
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Ejercicio1/README.md