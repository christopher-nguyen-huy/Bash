# Random settings

## Ctrl Left Right move word
- Put one of the 2 blocks in `~/.inputrc`
- Log out and log back in

```
"\e[C": forward-word	### Ctrl + right
"\e[D": backward-word	### Ctrl + left

"\eOC": forward-word	### Ctrl + right
"\eOD": backward-word	### Ctrl + left
```

## Enable colors
- Uncomment this line in `~/.bashrc`

```
#force_color_prompt=yes
```

## Kill process
http://www.cyberciti.biz/faq/kill-process-in-linux-or-terminate-a-process-in-unix-or-linux-systems/
Find the pid of process to be killed
```
ps aux | grep processname
```
The pid will be in the second column

`kill pid`
