# stdin reader and writer

Reads from stdin, then prints to stdout.


```bash
$ go run main.go
Greg
Hello => Greg
$ cat names.txt | go run main.go
Hello => John
Hello => William
Hello => James
Hello => Charles
Hello => George
Hello => Frank
Hello => Joseph
Hello => Thomas
Hello => Henry
```

```bash
$ go build -o greeter *.go
$ ./greeter
Greg
Hello => Greg
```
