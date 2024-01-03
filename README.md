# Common es una lista de recursos que pueden ser llamadados desde la terminal para facilitar tareas comunes en ciberseguridad.

las Listas de Comandos y recursos comunes fueron inspirados en post como [common](https://sirensecurity.io/blog/common/) por de **S1ren**  [Reverse Shell Cheat Sheet](https://pentestmonkey.net/cheat-sheet/shells/reverse-shell-cheat-sheet) por **Pentester Monkey** [HackTricks](https://book.hacktricks.xyz/welcome/readme) por **Carlos Polop** Y **PayloadAllTheThings**. 

Nota:

Algunos fueron modificados para funcionar con la instalación de SecLists a travez de los repositorios de Kali Linux.

### Dependencias:

1. **git**
2. **SecLists**

### Installación:

`sudo apt-get install seclists -y`

`sudo curl https://raw.githubusercontent.com/ArkCSI/common/main/common -o /bin/common; sudo chmod +x /bin/common`

### Uso:

`common`
`rshell`
`winAtt`
`linAtt`
`ftty`

### Referencias:

[S1ren Common Post](https://sirensecurity.io/blog/common/)

[SecLists](https://github.com/danielmiessler/SecLists)
https://book.hacktricks.xyz/welcome/readme
https://pentestmonkey.net/cheat-sheet/shells/reverse-shell-cheat-sheet
