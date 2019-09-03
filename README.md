# zsh change directory (cd) dot expansion

Extracted from the [prezto editor module](https://github.com/sorin-ionescu/prezto/tree/master/modules/editor).

Expands 

```
cd ...
``` 

to 

```
cd ../..
```  

and so forth in zsh.

Use this in combination with the 

```
setopt auto_cd
```

[zsh option](http://zsh.sourceforge.net/Doc/Release/Options.html) and you can omit the `cd` and just type `...` to change to the second directory above.

## Install with Antigen

```
antigen bundle wazum/zsh-directory-dot-expansion
```

## Install with zplug

```
zplug "wazum/zsh-directory-dot-expansion"
```

## oh-my-zsh

oh-my-zsh does something similar with aliases, see
https://github.com/robbyrussell/oh-my-zsh/blob/master/lib/directories.zsh
