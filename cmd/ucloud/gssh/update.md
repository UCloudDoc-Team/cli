{{indexmenu_n>4}}

## ucloud gssh update

Update GlobalSSH instance

### Synopsis

Update GlobalSSH instance, including port and remark attribute

```
ucloud gssh update [flags]
```

### Examples

```
ucloud gssh update --gssh-id uga-xxx --port 22
```

### Options

```
  --gssh-id     strings     Required. ResourceID of your GlobalSSH instances 

  --project-id     string   Optional. Override default project-id, see 'ucloud project list'
                            (default "org-oxjwoi") 

  --port     int            Optional. Port of SSH service. 

  --remark     string       Optional. Remark of your GlobalSSH. 

  --help, -h                help for update 

```

### Options inherited from parent commands

```
  --debug, -d   Running in debug mode 

  --json, -j    Print result in JSON format whenever possible 

```

### SEE ALSO

* [ucloud gssh](software/cli/cmd/ucloud/gssh)	 - Create,list,update and delete globalssh instance

