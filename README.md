### CLI structure

```
acf										                      "missing argument use `acf --help` to get help"
acf init								                    "initialize acf in this directory"
acf init <dir>							                "initialize acf in specified directory"
acf init --directory <dir> --duration <dur>	"initialize acf in a specified directory with a specified duration
acf remove								                  "remove acf in this directory"
acf pause								                    "pause acf in this directory"
acf pause --duration <dur>				          "pause acf in this directory for <dur> amount of time"
acf resume								                  "resume acf in this directory"
acf --list								                  "list all files in this directory and their persistance"
acf --persistance --enable --duration <dur> <files>	"enable persistances for <files> for duration <dur>"
acf --persistance --deisable <files>	      "disable persistance for <files>"
```

### Other requirements

- hidden `acf` file created in acf directory
- `acf` file should be human readable (JSON or toml)
