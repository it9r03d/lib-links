### todo

#### more ...
> useful, helpful, beneficial, wholesome, valuable, effective, advantageous, practical, salutary, adjuvant

* [termite](https://github.com/thestinger/termite)

* [NVM](https://github.com/creationix/nvm 'Node Version Manager - Simple bash script to manage multiple active node.js versions ') | [nodejs](https://github.com/nodejs/node 'Node.js JavaScript runtime') | [nodejs/Release
](https://github.com/nodejs/Release 'Node.js Foundation Release Working Group ') | [npm](https://github.com/npm/cli)

`PHP`
* [sebastian-bergmann](https://sebastian-bergmann.de/) | [github](https://github.com/sebastianbergmann)
* [publications](https://sebastian-bergmann.de/publications.html) | [presentations](https://sebastian-bergmann.de/presentations.html)
* https://thephp.cc/welcome

`sort`
* [tools&utils](/man/toolsandutils.md)
* [php-cli-tools](https://github.com/wp-cli/php-cli-tools 'A collection of tools to help with PHP command line utilities ')

`reorganize`

* `...`
`space`
* https://askubuntu.com/questions/5980/how-do-i-free-up-disk-space
* list-files
* * `find / -size +50M -type f -exec du -h {} \; | sort -n`
* * `find / -type f -size +1024k`
* * `find / -size +50000  -exec ls -lahg {} \;`
* show top 10 biggest subdirs in the current dir.
* * `du -skh * | sort -nr | head -10`
* tools
```
sudo apt-get install ncdu debian-goodies deborphan

sudo ncdu /    # lists all folders by size on the console (like the gui `baobab`)
dpigs -H       # shows large packages that you don't use
man deborphan  # finds packages that have no packages depending on them
deborphan --guess-all --libdevel | xargs apt-get -s purge
```

`colorize terminal`
* https://www.cyberciti.biz/faq/bash-shell-change-the-color-of-my-shell-prompt-under-linux-or-unix/

* https://www.tecmint.com/customize-bash-colors-terminal-prompt-linux/

* https://unix.stackexchange.com/questions/148/colorizing-your-terminal-and-shell-environment

