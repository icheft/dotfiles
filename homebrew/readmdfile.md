# How to read markdown file in terminal

### Install Pandoc and Lynx first

### Setting up the script
1. 
```
rmd(){
	pandoc $1 | lynx -stdin
}
```
insert the upon code into `~/.profile`

2.  
conduct `source ~/.profile` after that 

### Command
rmd ______/(filename).md


### Resources
[tosbourn.com](https://tosbourn.com/view-markdown-files-terminal/)
