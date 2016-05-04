nvm can help your to make multiple `nodejs` versions coexisting

# setup env
All of these steps are based on `ubuntu` v12.04 or v14.04.

## install nvm 
to make multiple nodejs versions coexisting

[how to install nvm](https://github.com/creationix/nvm)

after installation, must source .bashrc
```bash
. ~/.bashrc
```

And then you can use these commands
```bash
command -v nvm 
nvm ls
```


## install nodejs
install nodejs version v0.12, v4, v6
```bash
nvm install 0.12
nvm install 4
nvm install 6

nvm use 0.12

nvm alias default 6.0   # set v6.0 as the default version 
```


## setup gitbook to write this note

[reference](https://github.com/GitbookIO/gitbook-cli)

```bash
nvm install -g gitbook
nvm install -g gitbook-cli

cd my-book-proj
gitbook init
vi SUMMARY.md
gitbook serve
```

Now you can browse the book via http://localhost:3000 by default


# reference

## markdown 
[markdown cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)

[Markdown Cheatsheet2](http://assemble.io/docs/Cheatsheet-Markdown.html)


## setup git
TODO

## setup mongo
TODO

## othter tools useful
TODO

jsdoc, etc

