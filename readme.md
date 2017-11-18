# Basic terminal command for beginner, web designer and web developer (git bash in windows)
There are tons of commands. Therefore, I am sharing only essential 8 commands which make you a pro pc/mac/linux user. Windows user need to install [git](https://git-scm.com/) software. All commands you will be able use in gitbash.        


-----

### commands(8)
* `cd` - change directory
* `touch` 
* `mkdir` - make directory
* `cp` - copy
* `mv` - move
* `rm` - remove
* `pwd` - present working directory
* `ls` - listing
### flags(2)
flag always start with `-`
* `r` - recursive
* `f` - force         
### Identifiers(3)
* `*` - everything
* `.` - current directory
* `..` parent directory        

## Details

for removing and copying folder we need `r` flag       
### to change directory
~~~bash
cd <folderName>
~~~
### to make a file
~~~bash
touch <fileName> 
~~~

### to make a directory
~~~bash
mkdir  <folderName>
~~~

### to copy 
~~~bash
# copy file
cp <copyPath> <pastePath>
# copy folder
cp -r <copyPath> <pastePath>
~~~

### to move
~~~bash
mv <cutpath> <pastePath>
~~~

### to remove file
~~~bash
# to remove file
rm <fileName>
# to remove folder
rm -rf <folderName>
~~~

### to see what inside a directory
~~~bash
# to know current folder listing
ls
# to know some other folder listing
ls <folderPath>
~~~
### to know the present working directory
~~~bash
pwd
~~~


