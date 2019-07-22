{{indexmenu_n>6}}

## ucloud pathx uga delete-port

Delete port for uga instance

### Synopsis

Delete port for uga instance

```
ucloud pathx uga delete-port [flags]
```

### Options

```
  --project-id     string   Optional. Override default project-id, see 'ucloud project list'
                            (default "org-oxjwoi") 

  --uga-id     string       Required. Resource ID of uga instance to delete port 

  --protocol     string     Required. accept values: tcp,udp 

  --port     strings        Required. Single port or port range, separated by ',', for example
                            80,3000-3010 

  --help, -h                help for delete-port 

```

### Options inherited from parent commands

```
  --debug, -d   Running in debug mode 

  --json, -j    Print result in JSON format whenever possible 

```

### SEE ALSO

* [ucloud pathx uga](software/cli/cmd/ucloud/pathx/uga)	 - Create,list,update and delete pathx uga instances

