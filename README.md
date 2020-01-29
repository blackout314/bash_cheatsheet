# bash_cheatsheet #
fast personal cheatsheet

**Table Of Contents**
- [if](#if)
  - [string comparison](#string-comparison)


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
