# bm-bookmarks (very original I know)
Adds, removes, navigates to a saved bookmark in linux (ubuntu) terminal. Also shows a list of all saved bookmarks.

####Installation
```
git clone https://github.com/frasaleksander/bm-bookmarks.git ~/.bm-bookmarks
```

####Making life easier with aliases
Add following aliases to .bashrc file. .bashrc is located in home directory. Open terminal write `sudo nano ~/.bashrc`. Append these lines to the end of the file. Save file with ctrl+x
```bash
alias bmadd=". ~/.bm-bookmarks/bm add"
alias bmrm=". ~/.bm-bookmarks/bm remove"
alias bmto=". ~/.bm-bookmarks/bm goto"
alias bmls=". ~/.bm-bookmarks/bm list"
```
