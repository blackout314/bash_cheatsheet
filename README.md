# bash_cheatsheet #
fast personal cheatsheet


## if ##
### string comparison ###
```bash
VAR="hello"
if [ -n "$VAR" ]; then
    echo "VAR is not empty"
fi
```

```bash
VAR=""
if [ -z "$VAR" ]; then
    echo "VAR is empty"
fi
```
