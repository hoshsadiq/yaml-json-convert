# yaml-json-convert

A command line tool to easily convert YAML to JSON and visa versa

### Usage

```
$ yaml2json examples/example.yaml
{"github":"https://github.com/hoshsadiq","user":"hosh"}

$ json2yaml examples/example.json
github: https://github.com/hoshsadiq
user: hosh

$ yaml2json examples/example.yaml | json2yaml
github: https://github.com/hoshsadiq
user: hosh

$ json2yaml examples/example.json | yaml2json
{"github":"https://github.com/hoshsadiq","user":"hosh"}
```

### Building

Run the `./build` script to build all platforms automatically. You will need to have golang installed
