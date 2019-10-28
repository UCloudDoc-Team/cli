

## ucloud udisk restore

Restore udisk from snapshot

### Synopsis

Restore udisk from snapshot

```
ucloud udisk restore [flags]
```

### Options

```
  --snapshot-id     strings   Required. Resourece ID of the snapshots to restore from 

  --project-id     string     Optional. Assign project-id 

  --region     string         Optional. Assign region 

  --zone     string           Optional. Assign availability zone 

  --help, -h                  help for restore 

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

* [ucloud udisk](developer/cli/cmd/ucloud/udisk)	 - Read and manipulate udisk instances

