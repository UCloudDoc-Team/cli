

## ucloud mysql backup list

List backups of MySQL instance

### Synopsis

List backups of MySQL instance

```
ucloud mysql backup list [flags]
```

### Options

```
  --udb-id     string        Optional. Resource ID of UDB for list the backups of the specifid UDB 

  --backup-id     string     Optional. Resource ID of backup. List the specified backup only 

  --backup-type     string   Optional. Backup type. Accept values:auto or manual 

  --db-type     string       Optional. Only list backups of the UDB of the specified DB type 

  --begin-time     string    Optional. Begin time of backup. For example, 2019-02-26/11:21:39 

  --end-time     string      Optional. End time of backup. For example, 2019-02-26/11:31:39 

  --region     string        Optional. Override default region for this command invocation,
                             see 'ucloud region' 

  --zone     string          Optional. Override default availability zone for this command
                             invocation, see 'ucloud region' 

  --project-id     string    Optional. Override default project-id for this command
                             invocation, see 'ucloud project list' 

  --offset     int           Optional. The index(a number) of resource which start to list 

  --limit     int            Optional. The maximum number of resources per page (default 100) 

  --help, -h                 help for list 

```

### Options inherited from parent commands

```
  --base-url     string       Set base-url to override the base-url in local config file 

  --debug, -d                 Running in debug mode 

  --json, -j                  Print result in JSON format whenever possible 

  --max-retry-times     int   Set max-retry-times to override the max-retry-times in local
                              config file (default -1) 

  --private-key     string    Set private-key to override the private-key in local config file 

  --profile, -p string        Specifies the configuration for the operation 

  --public-key     string     Set public-key to override the public-key in local config file 

  --timeout-sec     int       Set timeout-sec to override the timeout-sec in local config file 

```

### SEE ALSO

* [ucloud mysql backup](developer/cli/cmd/ucloud/mysql/backup)	 - List and manipulate backups of MySQL instance

