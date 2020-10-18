<!-- PROJECT LOGO -->
<br />
<p align="center">

  <h1 align="center">Engineering Toolkit</h1>

  <p align="center">
    A collection of tools to make your engineering assignments easier.
    <br />
  </p>
</p>

<!-- ABOUT THE PROJECT -->
## What is it?

This toolkit includes several bash scripts to automate some repetative tasks. 


**Vix**
(short for vim executable) is a tool for quickly creating bash shell scripts. 
It will create a file with `#!/bin/bash` at the top, make it executable with `chmod +x`, then open with vim. All with one command.

**Pack** 
Is a tool for quickly and easily packaging up your assignments into a .tgz file for submission. 
Instead of remembering all the options and commands simply type `pack` and follow the instructions.

**Vice**
Is a tool for quickly creating ngspice network files from templates, editing, and running them.
It includes optional reference lines for more complicated element types such as CCVS and VCVS.
Vice also supports multiple text editors such as vim, emacs, and nano. 



**Push** 
is a simplified method of pushing your github files. 
In puts `git add .`, `git commit`, and `git push` into a single command.
NOTE: The commit message will be `AUTO COMMIT: <date>` with no addtitional info. 
This tool is not recommended for group projects where an actual commit message is needed.

**Pull**
is the same as Push, but for pulling from github. 
It simply runs `git pull`. 
This tool is very useful because it saves you from typing three extra letters. 

**Stat**
(Short for status) is an improvment to the `batt` script which shows your battery level. 
It displays the time, date, battery level, time left on battery/time until charged, and your IP address. 


<!-- GETTING STARTED -->
## Getting Started

If you want to install all tools simply follow the installation steps below. 
If you only want one tool, manually copy it to `/usr/local/bin` after cloning.

### Installation

1. Clone the repo
```sh
git clone https://github.com/github_username/repo_name.git
```
2. cd into the cloned folder
```sh
cd toolkit
```
3. Run the installer script
```sh
./install_toolkit
```
That's it. You're done.
**Please read the usage instructions below.** 


**TO UPDATE TOOLS LATER**
1. cd into the cloned folder
```sh
cd toolkit
```
2. update with git pull
```sh
git pull
```
3. run the installer again
```sh
./install_toolkit
```
Now you are running the latest version!

<!-- USAGE EXAMPLES -->
## Usage

**Vix**
```sh
vix myscript
```
Will create a shell script called myscript, add !#/bin/bash, and make it executable with `chmod +x`. It will then open in vim.

```sh
vix myscript o
```
Will allow you to overwrite an existing file with the same name.


**Pack**
IMPOTANT: Before running edit the line containing $NAME to match your name.
cd into the folder you want to pack.
Then simply 
```sh
pack
``` 
and follow the prompts.




<!-- ROADMAP -->
## Roadmap

See the [open issues](https://github.com/github_username/repo_name/issues) for a list of proposed features (and known issues).



<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE` for more information.



<!-- CONTACT -->
## Contact

John Soupir - Email: UMary student email.


