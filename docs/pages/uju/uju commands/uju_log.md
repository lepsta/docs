## uju log

Shows the history of the current state. If file name is specified it will show history of that file in the current state.

### Synopsis

Shows the history of the current state. If file name is specified it will show history of that file in the current state.

```
uju log [-s start from page] [-z page size] [-b branch</stream>] [filename] [flags]
```

### Options

```
  -r, --branch</stream> string   Use this branch/stream [r]eference
  -f, --filename string          Shows the history of a file
  -g, --git                      Shows the git commit log
  -h, --help                     help for log
  -j, --json                     Returns output as a JSON string
  -z, --page_size int            Number of entries to return at a time: 'page si[z]e' (default 20)
  -b, --start_page int           Page to start from: '[b]egin at' (default 1)
```

### Options inherited from parent commands

```
  -A, --deamon_address string   The URL of the System daemon (default "http://localhost:6060")
      --repo string             Repo ID, name or path to use for the current operation
```

### SEE ALSO

* [uju](uju.md)	 - A version control tool for source code

###### Auto generated by spf13/cobra on 6-Sep-2020