# Bashrc

This is my .bashrc.

## Features

* An alias `alert` for showing an alert after a command is done
* Infinite bash history


## Manual setup

Make bash completion work for aliases.

https://unix.stackexchange.com/a/332522

```bash
mkdir ~/.bash_completion.d
curl https://raw.githubusercontent.com/cykerway/complete-alias/master/complete_alias \
     > ~/.bash_completion.d/complete_alias
```

