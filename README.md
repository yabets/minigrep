Tasks
#1
The first task is to make minigrep accept its two command line arguments: the file path and a string to search for. That is, we want to be able to run our program with cargo run, two hyphens to indicate the following arguments are for our program rather than for cargo, a string to search for, and a path to a file to search in, like so:

```bash
$ cargo run -- searchstring example-filename.txt
```

