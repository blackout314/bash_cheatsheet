![bash](bash-logo.png)

# bash_cheatsheet #
fast personal cheatsheet

**Table Of Contents**
- [if](#if)
  - [string comparison](#string-comparison)
- [real use](#real-use)


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

## real use ##
### execute cmd every $time ###
```bash
#!/bin/sh
while [ true ]
do
    sh special_svn_script.sh
    sleep 10
done
```
