

## ucloud mysql db restore

Create MySQL instance and restore the newly created db to the specified DB at a specified point in time

### Synopsis

Create MySQL instance and restore the newly created db to the specified DB at a specified point in time

```
ucloud mysql db restore [flags]
```

### Options

```
  --name     string              Required. Name of UDB instance to create 

  --src-udb-id     string        Required. Resource ID of source UDB 

  --restore-to-time     string   Required. The date and time to restore the DB to. Value must
                                 be a time in Universal Coordinated Time (UTC) format.Example:
                                 2019-02-23T23:45:00Z 

  --region     string            Optional. Override default region for this command
                                 invocation, see 'ucloud region' 

  --zone     string              Optional. Override default availability zone for this command
                                 invocation, see 'ucloud region' 

  --project-id     string        Optional. Override default project-id for this command
                                 invocation, see 'ucloud project list' 

  --disk-type     string         Optional. Disk type. The default is to be consistent with the
                                 source database. Accept values: normal, ssd 

  --charge-type     string       Optional. Enumeration value.'Year',pay yearly;'Month',pay
                                 monthly; 'Dynamic', pay hourly; 'Trial', free trial(need
                                 permission) (default "Month") 

  --quantity     int             Optional. The duration of the instance. N years/months.
                                 (default 1) 

  --async, -a                    Optional. Do not wait for the long-running operation to finish 

  --help, -h                     help for restore 

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

* [ucloud mysql db](developer/cli/cmd/ucloud/mysql/db)	 - Manange MySQL instances

