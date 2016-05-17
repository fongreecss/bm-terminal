# bm-terminal
Adds, removes, navigates to saved bookmarks in linux (ubuntu) terminal.  
*works only on folders.

####Installation
```bash
git clone https://github.com/frasaleksander/bm-terminal.git ~/.bm-terminal
```

####Making life easier with aliases
Add following aliases to the **.bashrc** file. .bashrc is located in the home directory. Open terminal and write **`sudo nano ~/.bashrc`** in it. **Append** these lines at the end of the .bashrc file. **CTRL+x** to **save** the file.
```bash
alias bmadd=". ~/.bm-terminal/bm add"
alias bmrm=". ~/.bm-terminal/bm remove"
alias bmto=". ~/.bm-terminal/bm goto"
alias bmls=". ~/.bm-terminal/bm list"
```
**You should restart your terminal after saving the file!**  

####Adding bookmark 
cd to directory you want to bookmark (for example `cd /bin`)
```bash
bmadd binbm
```
Directory bin is now saved under binbm bookmark name.

####Navigating to bookmark
```bash
bmto binbm
```

####Removing bookmark
```bash
bmrm binbm
```

####Listing all saved bookmarks
```bash
bmls
```
