{{indexmenu_n>6}}

## ucloud mysql db restart

Restart MySQL instances by udb-id

### Synopsis

Restart MySQL instances by udb-id

```
ucloud mysql db restart [flags]
```

### Options

```
  --udb-id     strings      Required. Resource ID of UDB instances to restart 

  --region     string       Optional. Override default region, see 'ucloud region' (default
                            "cn-sh2") 

  --zone     string         Optional. Override default availability zone, see 'ucloud region'
                            (default "cn-sh2-02") 

  --project-id     string   Optional. Override default project-id, see 'ucloud project list'
                            (default "org-oxjwoi") 

  --async, -a               Optional. Do not wait for the long-running operation to finish. 

  --help, -h                help for restart 

```

### Options inherited from parent commands

```
  --debug, -d   Running in debug mode 

  --json, -j    Print result in JSON format whenever possible 

```

### SEE ALSO

* [ucloud mysql db](software/cli/cmd/ucloud/mysql/db)	 - Manange MySQL instances

