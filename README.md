Asus@Will MINGW64 ~ (master)
$ mkdir ejercicios

Asus@Will MINGW64 ~ (master)
$ ls
'3D Objects'/
 AppData/
 Apple/
 CmapToolsLogs/
'Configuración local'@
 Contacts/
 Cookies@
'Creative Cloud Files'/
'Datos de programa'@
 Desktop/
 Documents/
 Downloads/
'Entorno de red'@
 Favorites/
 IdeaProjects/
 Impresoras@
 InstallAnywhere/
 IntelGraphicsProfiles/
 Links/
'Menú Inicio'@
 MicrosoftEdgeBackups/
'Mis documentos'@
 Music/
 NTUSER.DAT
 NTUSER.DAT{53b39e88-18c4-11ea-a811-000d3aa4692b}.TM.blf
 NTUSER.DAT{53b39e88-18c4-11ea-a811-000d3aa4692b}.TMContainer00000000000000000001.regtrans-ms
 NTUSER.DAT{53b39e88-18c4-11ea-a811-000d3aa4692b}.TMContainer00000000000000000002.regtrans-ms
 OneDrive/
 Pictures/
 Plantillas@
 Reciente@
'Saved Games'/
 Searches/
 SendTo@
 Videos/
 ejercicios/
 iCloudDrive/
 ntuser.dat.LOG1
 ntuser.dat.LOG2
 ntuser.ini

Asus@Will MINGW64 ~ (master)
$ cd ejercicios/

Asus@Will MINGW64 ~/ejercicios (master)
$ ls

Asus@Will MINGW64 ~/ejercicios (master)
$ cd

Asus@Will MINGW64 ~ (master)
$ pwd
/c/Users/Asus

Asus@Will MINGW64 ~ (master)
$ cd ejercicios/

Asus@Will MINGW64 ~/ejercicios (master)
$ git initi
git: 'initi' is not a git command. See 'git --help'.

The most similar command is
        init

Asus@Will MINGW64 ~/ejercicios (master)
$ git init
Initialized empty Git repository in C:/Users/Asus/ejercicios/.git/

Asus@Will MINGW64 ~/ejercicios (master)
$ git add .

Asus@Will MINGW64 ~/ejercicios (master)
$ git commit -m "Version inicial"
[master (root-commit) da1ee05] Version inicial
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 ejercicios1/README.md

Asus@Will MINGW64 ~/ejercicios (master)
$ git log:
git: 'log:' is not a git command. See 'git --help'.

The most similar command is
        log

Asus@Will MINGW64 ~/ejercicios (master)
$ git log
commit da1ee05526c129f5923bef8da573c147422eb503 (HEAD -> master)
Author: William Perez Rojas <williamleonardo1785@gmail.com>
Date:   Thu Mar 2 13:29:54 2023 -0500

    Version inicial

Asus@Will MINGW64 ~/ejercicios (master)
$ ^C

Asus@Will MINGW64 ~/ejercicios (master)
$ git commit "Agrega solucion primer ejercicio"
error: pathspec 'Agrega solucion primer ejercicio' did not match any file(s) known to git

Asus@Will MINGW64 ~/ejercicios (master)
$ git commit -m "Agrega solucion primer ejercicio"
[master bb75182] Agrega solucion primer ejercicio
 3 files changed, 3 insertions(+)
 rename ejercicios1/README.md => .vscode/ejercicios1 (100%)
 create mode 100644 .vscode/settings.json
 create mode 100644 README.md

Asus@Will MINGW64 ~/ejercicios (master)
$ git commit -m "Agregue el archivo README.md"
On branch master
nothing to commit, working tree clean

Asus@Will MINGW64 ~/ejercicios (master)
$ rm
rm: missing operand
Try 'rm --help' for more information.

Asus@Will MINGW64 ~/ejercicios (master)
$ rm /ejercicios
rm: cannot remove '/ejercicios': No such file or directory

Asus@Will MINGW64 ~/ejercicios (master)
$ code README.md
