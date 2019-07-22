{{indexmenu_n>4}}

## ucloud redis restart

Restart redis instances of master-replica type

### Synopsis

Restart redis instances of master-replica type

```
ucloud redis restart [flags]
```

### Options

```
  --umem-id     strings     Required. Resource ID of redis instances to restart 

  --project-id     string   Optional. Override default project-id, see 'ucloud project list'
                            (default "org-oxjwoi") 

  --region     string       Optional. Override default region, see 'ucloud region' (default
                            "cn-sh2") 

  --zone     string         Optional. Override default availability zone, see 'ucloud region'
                            (default "cn-sh2-02") 

  --help, -h                help for restart 

```

### Options inherited from parent commands

```
  --debug, -d   Running in debug mode 

  --json, -j    Print result in JSON format whenever possible 

```

### SEE ALSO

* [ucloud redis](software/cli/cmd/ucloud/redis)	 - List and manipulate redis instances

