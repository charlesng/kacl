kacl
====

Command line utility for maintaining a changelog in the [Keep a
Changelog](http://keepachangelog.com/en/1.0.0/) format

Install
-------

```
go install -v github.com/nicwest/kacl
```

Usage
-----

```
$ kacl
Command line utility for maintaining a changelog in the 
Keep a Changelog format

http://keepachangelog.com/en/1.0.0/

Usage:
  kacl [command]

Available Commands:
  added       Add a change to the list of Unreleased additions
  changed     Add a change to the list of Unreleased changes
  deprecated  Add a change to the list of Unreleased deprecations
  fixed       Add a change to the list of Unreleased fixes
  help        Help about any command
  init        Initialize a CHANGELOG.md file
  release     Create a new release
  removed     Add a change to the list of Unreleased removals
  security    Add a change to the list of Unreleased security updates

Flags:
      --config string   config file (default is $HOME/.kacl.yaml)
  -h, --help            help for kacl

Use "kacl [command] --help" for more information about a command.
```
