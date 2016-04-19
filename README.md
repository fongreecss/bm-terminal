# bm-bookmarks (very original I know)
Adds, removes, navigates to a saved bookmark in linux (ubuntu) terminal. Also shows a list of all saved bookmarks. 
*works only on folders

####Installation
```bash
git clone https://github.com/frasaleksander/bm-bookmarks.git ~/.bm-bookmarks
```

####Making life easier with aliases
Add following aliases to .bashrc file. .bashrc is located in home directory. Open terminal write `sudo nano ~/.bashrc` in it. Append these lines to the end of the .bashrc file. ctrl+x to save the file.
```bash
alias bmadd=". ~/.bm-bookmarks/bm add"
alias bmrm=". ~/.bm-bookmarks/bm remove"
alias bmto=". ~/.bm-bookmarks/bm goto"
alias bmls=". ~/.bm-bookmarks/bm list"
```
You should restart your terminal after saving the file!  

####Adding bookmark 
cd to directory you want to bookmark (for example `cd /bin`)
```bash
bmadd binbm
```
directory /bin is now saved under binbm

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
