# Yarn v3 Bin Link Bug

```shell
$ yarn

$ ls -l ./node_modules/.bin/tsc
lrwxrwxrwx 1 avaly avaly 25 Jun 30 11:35 ./node_modules/.bin/tsc -> ../typescript-3.9/bin/tsc*

$ ./node_modules/.bin/tsc -v
Version 3.9.10
```
