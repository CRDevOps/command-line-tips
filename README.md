# Command Line Tips

Run the last command:

```bash
$ !!
```

Run the last command as root:

```bash
$ sudo !!
```

Run the last command, starting with pattern

```bash
$ !<pattern>
```

Print the last command, starting with pattern

```bash
$ !<pattern>:p
```

Open Preview.app from command line (should work also for any other program):

```bash
$ open /Applications/Preview.app
```

Copy your current work directory to your clipboard (mac only):

```bash
$ printf $(pwd) | pbcopy
```

# My Aliases

This is a list of my favorite command aliases. Feel free to copy and place them into your `~/.bash_profile` file.

```
alias s="cd .."
alias ll='ls -l'
alias ifconfigme='curl ifconfig.me'
```

# My ~/.inputrc

```
"\e[A":     history-search-backward
"\e[B":     history-search-forward
"\eOA":     history-search-backward
"\eOB":     history-search-forward
```