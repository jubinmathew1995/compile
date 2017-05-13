# compile

### execution of source code
Tired ? tired of compling the source code of c/c++ program and then Executing the object file to complete the execution of your c/c++ program.
compile command helps to compile and execute your c/c++ program directly using a single command i.e. 'compile'.

### Prerequisities
* g++
* gcc

#### for Debian / Ubuntu / Debian derivatives
```
  apt-get install g++
  apt-get install gcc
```
#### for Arch Linux / arch derivatives
```
sudo pacman -Sy base-devel
```

### install
compile is a shell script, so drop it somewhere and make sure it's added to your $PATH. Or you can use the following one-liner:

```
sudo sh -c "curl https://raw.githubusercontent.com/jubinmathew1995/compile/master/compile -o /usr/local/bin/compile && chmod +x /usr/local/bin/compile"
```

### usage
just give your source code file name as input to the compile command to obtain the execution results.

    $ compile filename.cpp
    .
    OUTPUT OF YOUR EXECUTING program
    .
    $

same can be done in case of c program.

    $ compile c_file_name.c
    .
    OUTPUT OF YOUR EXECUTING program
    .
    $
