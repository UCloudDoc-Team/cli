{{indexmenu_n>5}}

## ucloud pathx uga add-port

Add port for uga instance

### Synopsis

Add port for uga instance

```
ucloud pathx uga add-port [flags]
```

### Options

```
  --project-id     string   Optional. Override default project-id, see 'ucloud project list'
                            (default "org-oxjwoi") 

  --uga-id     string       Required. Resource ID of uga instance to add port 

  --protocol     string     Required. accept values: tcp,udp 

  --port     strings        Required. Single port or port range, separated by ',', for example
                            80,3000-3010 

  --help, -h                help for add-port 

```

### Options inherited from parent commands

```
  --debug, -d   Running in debug mode 

  --json, -j    Print result in JSON format whenever possible 

```

### SEE ALSO

* [ucloud pathx uga](software/cli/cmd/ucloud/pathx/uga)	 - Create,list,update and delete pathx uga instances

