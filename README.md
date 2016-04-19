# bm-bookmarks (very original I know)
Adds, removes, goes to bookmark in linux (ubuntu) terminal. Also shows a list of all saved bookmarks.

####Installation
```
git clone https://github.com/frasaleksander/bm-bookmarks.git ~/.bm-bookmarks
```

####Making life easier with aliases
add folowing aliases to .bashrc file which is located in home directory. Move there with command `cd ~`
```bash
alias bmadd=". ~/.bm-bookmarks/bm add"
alias bmrm=". ~/.bm-bookmarks/bm remove"
alias bmto=". ~/.bm-bookmarks/bm goto"
alias bmls=". ~/.bm-bookmarks/bm list"
```
