# bmofetch

A neofetch theme inspired by BMO from Adventure Time with a cowsay like speech bubble.\
you can find the complete neofetch-themes repository at:\
https://github.com/Chick2D/neofetch-themes/blob/main/small/bmofetch/

![](https://cdn.discordapp.com/attachments/840232870491979807/1268214715776110612/bmofetch.gif?ex=66ab9c7e&is=66aa4afe&hm=3a2297c0d30efc7ca4b9d7a7121d68080c3c92ad6f13235d4f43d34cf29045d7&)

- [bmofetch](#bmofetch)
  - [Installation](#installation)
  - [Change the speech bubble text](#change-the-speech-bubble-text)
  - [Input suported by bmosay.sh](#input-suported-by-bmosaysh)


## Installation
requires neofetch to be installed.

  1. Clone the repository:
```bash
  git clone
```
2. Copy the bmofetch folder to your neofetch themes directory:
```bash
cp -a path_to_bmofetch/bmofetch ~/.config/neofetch/
```
3. Run neofetch with the bmofetch.conf file:
```bash
neofetch --config ~/.config/neofetch/bmofetch/bmofetch.conf
```

## Change the speech bubble text

You can change the speech bublle text by running [bmosay.sh](https://github.com/donatienLeray/bmofetch/bmosay.sh) in your terminal:
```bash
 sh path_to_bmofetch/bmosay.sh "your text here"
```
**SYNOPSIS:\
  sh .config/neofetch/bmofetch/bmosay.sh [options] \<argument\>**

**OPTIONS:**\
&nbsp;&nbsp;-v, --verbose&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Enable verbose mode.(prints debug messages)\
&nbsp;&nbsp;-q, --quiet&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp; &nbsp; &nbsp;Suppress output.\
&nbsp;&nbsp;-r, --random &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Specify a file to get a random line from.\
&nbsp;&nbsp;-h, --help &nbsp;&nbsp;&nbsp;&nbsp; &nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Display help message and exit.\
&nbsp;&nbsp;-vq, -qv &nbsp; &nbsp; &nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Enable both verbose and quiet mode.(only prints debug messages)\
&nbsp;&nbsp;-\*\*, -\*\*\*&nbsp; &nbsp; &nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Any combination of r, v, q can be used instead  of the above

**EXAMPLES:**
```bash
sh .config/neofetch/bmofetch/bmosay.sh "Hello, world!"\
sh .config/neofetch/bmofetch/bmosay.sh -vq --random file.txt\
sh .config/neofetch/bmofetch/bmosay.sh -qr file.txt\
sh .config/neofetch/bmofetch/bmosay.sh --help
```

## Input suported by bmosay.sh
\+ supports utf-8 characters.\
\- newlines and carriage returns are not supported yet.\
\- multiple spaces as well as leading and trailing spaces are ignored.

