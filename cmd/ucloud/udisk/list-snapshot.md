# ucloud udisk list-snapshot

List snaphosts

## Synopsis

List snaphosts

```
ucloud udisk list-snapshot [flags]
```

## Options

```
  --project-id     string     Optional. Assign project-id 

  --region     string         Optional. Assign region 

  --zone     string           Optional. Assign availability zone 

  --snaphost-id     strings   Optional. Resource ID of snapshots to list 

  --uhost-id     string       Optional. Snapshots of the uhost 

  --disk-id     string        Optional. Snapshots of the udisk 

  --offset     int            Optional. Offset 

  --limit     int             Optional. Limit, length of snaphost list (default 50) 

  --help, -h                  help for list-snapshot 

```

## Options inherited from parent commands

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

## SEE ALSO

* [ucloud udisk](cli/cmd/ucloud/udisk)	 - Read and manipulate udisk instances

