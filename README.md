# minigrep
Small version of the `grep` command line tool, that searches for a given string inside a text file.

You can test it with the `poem.txt` file in the repo or with your own text file by running:

```
cargo run <search> <filename.txt>
```

The search is case sensitive by default. If you want to make it case insensitive you just need to set the `CASE_INSENSITIVE` environment variable to any value, for example:

```
CASE_INSENSITIVE=1
```