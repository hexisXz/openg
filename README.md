# openg
search google inside the terminal in openBSD!


# usage 
type:
```sh
openg -s {whatever you want to search}
```
example:
```sh
openg -s openBSD
```

# how to install
paste this in the terminal:
```sh
doas pkg_add py3-pip 

pip install pipx

pipx install html2text 

ftp https://raw.githubusercontent.com/hexisXz/openg/main/install && chmod +x install && sh install
```

or:

```sh
doas pkg_add py3-pip 

pip install pipx

pipx install html2text 

curl "https://raw.githubusercontent.com/hexisXz/openg/main/install" > install && chmod +x install && sh install
```


# uninstall
to uninstall paste this in the terminal
```sh
ftp https://raw.githubusercontent.com/hexisXz/openg/main/uninstall && chmod +x uninstall && sh uninstall
```
or
```sh
curl "https://raw.githubusercontent.com/hexisXz/openg/main/uninstall" > uninstall && chmod +x uninstall && sh uninstall  
```
