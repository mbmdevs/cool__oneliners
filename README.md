# cool__oneliners
#### A simple Repo to store & share all the rare oneliners I find

## 01 How to see what compiler/gcc version was used to compile a binary
> `objdump -s --section .comment binaryName`  
-s returns the full content of that section, --section returns info about that section only.  
.comment is the section  we want to read and lastly binaryName is the file we want to read from
>
> `strings binaryName | grep -i gcc` if you know the compiler is gcc 
