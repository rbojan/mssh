# mssh

mssh aka. multi-ssh is a lightweight script to execute ssh commands in parallel on multiple hosts

```
mssh du -h -d 1
```

`mssh` assumes that you got a `.mssh` file in your current directory.

If not you can set the location via `export MSSH_FILE=~/.mssh`
