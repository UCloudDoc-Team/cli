{{indexmenu_n>3}}

## ucloud mysql logs download

Display url of an archive(log file)

### Synopsis

Display url of an archive(log file)

```
ucloud mysql logs download [flags]
```

### Examples

```
ucloud mysql logs download --udb-id udb-urixxx/test.cli1 --archive-id 35044
```

### Options

```
  --archive-id     int      Required. ArchiveID of archive to download 

  --udb-id     string       Required. Resource ID of UDB which the archive belongs to 

  --region     string       Optional. Override default region, see 'ucloud region' (default
                            "cn-sh2") 

  --zone     string         Optional. Override default availability zone, see 'ucloud region'
                            (default "cn-sh2-02") 

  --project-id     string   Optional. Override default project-id, see 'ucloud project list'
                            (default "org-oxjwoi") 

  --help, -h                help for download 

```

### Options inherited from parent commands

```
  --debug, -d   Running in debug mode 

  --json, -j    Print result in JSON format whenever possible 

```

### SEE ALSO

* [ucloud mysql logs](software/cli/cmd/ucloud/mysql/logs)	 - List and manipulate logs of MySQL instance

