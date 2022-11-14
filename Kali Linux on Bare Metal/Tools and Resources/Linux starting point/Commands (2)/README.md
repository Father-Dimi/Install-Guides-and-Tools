# Starting Point

## This section focuses on the linux command line and its commands.


There are many linux commands, if i went through all of them id end up with the arch wiki, this will focus on the more important ones


### Touch
touch is the command to make new files for example, if you wish to make a file named "file" in the .txt format in the directory your in right now you would type `touch file.txt`


### Mkdir
mkdir is the command to make a directory, if you would wish to make a directory named "Linux" you would type `mkdir Linux`.

 You may also append a -p after mkdir (-p stands for parent) if you wish to make multiple directories within one, such as if you wish to make linux/filesystem but the linux directory does not exist you would get this message 

`cannot create linux/filesystem, directory does not exist.` 

this is because the "linux"directory does not exist, you may create linux and filesystem using the command `mkdir -p linux/filesystem`


### Cd
cd stands for "change directory", its pretty self-explanitory, you use this command for changing into another directory.

### Pwd
pwd stands for "print working directory" so when you type this command it will show you what directory (folder) you are in.

### File
in linux, when you create a file its file extension may not always represent its true file type, i could rename a  .png file to .jpeg and it would stay at .png. you can use the file command to see that kind of file format the file is in example: `file picture.png`

### Cat
cat is used to view the contents of any file that contains readable text. if you have a .bashrc file that you would like to see the contents of you would type `cat ~/.bashrc` and it would show you the text present in the folder. it all shows in your terminal, because of this using cat for large files isnt that effective.

### Cp
cp stands for "copy" it is pretty self-explanitory. you use it to copy files. if you would like to move __~Downloads/example__ to __~Documents/__ you would type `cp ~/Downloads/example ~/Documents/` and it would copy the file

### Mv
mv stands for "move" you may use it in the same context of cp but remember instead of copying the file it actually moves it

### Man
Man and/or manpages is the terminal app that shows documentation for a certain app. say if i wanted to see the documentation in terminal for pacman (arch-based package manager) i would type in the terminal `man pacman` and i would then see the documentation for it

### The Arch Wiki.
even if you are not running arch or an arch-based system the [Arch Wiki](https://wiki.archlinux.org/) is very very useful. if there is documentation for something, it exist on the arch wiki, usually you can get the gist on how to use a certain tool for linux by googling it along side "arch-wiki"


## Final Note
Just remember none of this comes instantly, you will not be some linux wizard in 1 week, ive been using linux over 4 years and i still learn stuff almost daily.