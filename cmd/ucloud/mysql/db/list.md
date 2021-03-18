# ucloud mysql db list

List MySQL instances

## Synopsis

List MySQL instances

```
ucloud mysql db list [flags]
```

## Options

```
  --udb-id     string       Optional. List the specified mysql 

  --project-id     string   Optional. Override default project-id for this command invocation,
                            see 'ucloud project list' 

  --region     string       Optional. Override default region for this command invocation, see
                            'ucloud region' 

  --zone     string         Optional. Override default availability zone for this command
                            invocation, see 'ucloud region' 

  --limit     int           Optional. The maximum number of resources per page (default 100) 

  --offset     int          Optional. The index(a number) of resource which start to list 

  --include-slaves          Optional. When specifying the udb-id, whether to display its
                            slaves together. Accept values:true, false 

  --help, -h                help for list 

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

* [ucloud mysql db](cli/cmd/ucloud/mysql/db)	 - Manange MySQL instances

