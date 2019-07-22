{{indexmenu_n>4}}

## ucloud mysql logs delete

Delete log archives(log files)

### Synopsis

Delete log archives(log files)

```
ucloud mysql logs delete [flags]
```

### Examples

```
ucloud mysql logs delete --archive-id 35025
```

### Options

```
  --archive-id     ints     Optional. ArchiveID of log archives to delete 

  --region     string       Optional. Override default region, see 'ucloud region' (default
                            "cn-sh2") 

  --zone     string         Optional. Override default availability zone, see 'ucloud region'
                            (default "cn-sh2-02") 

  --project-id     string   Optional. Override default project-id, see 'ucloud project list'
                            (default "org-oxjwoi") 

  --help, -h                help for delete 

```

### Options inherited from parent commands

```
  --debug, -d   Running in debug mode 

  --json, -j    Print result in JSON format whenever possible 

```

### SEE ALSO

* [ucloud mysql logs](software/cli/cmd/ucloud/mysql/logs)	 - List and manipulate logs of MySQL instance

