{{indexmenu_n>5}}

## ucloud mysql db stop

Stop MySQL instances by udb-id

### Synopsis

Stop MySQL instances by udb-id

```
ucloud mysql db stop [flags]
```

### Options

```
  --udb-id     strings      Required. Resource ID of UDB instances to stop 

  --region     string       Optional. Override default region, see 'ucloud region' (default
                            "cn-sh2") 

  --zone     string         Optional. Override default availability zone, see 'ucloud region'
                            (default "cn-sh2-02") 

  --project-id     string   Optional. Override default project-id, see 'ucloud project list'
                            (default "org-oxjwoi") 

  --force                   Optional. Stop UDB instances by force or not 

  --async, -a               Optional. Do not wait for the long-running operation to finish. 

  --help, -h                help for stop 

```

### Options inherited from parent commands

```
  --debug, -d   Running in debug mode 

  --json, -j    Print result in JSON format whenever possible 

```

### SEE ALSO

* [ucloud mysql db](software/cli/cmd/ucloud/mysql/db)	 - Manange MySQL instances

