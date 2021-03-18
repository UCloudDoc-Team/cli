# ucloud mysql db delete

Delete MySQL instances by udb-id

## Synopsis

Delete MySQL instances by udb-id

```
ucloud mysql db delete [flags]
```

## Options

```
  --udb-id     strings      Required. Resource ID of UDB instances to delete 

  --region     string       Optional. Override default region for this command invocation, see
                            'ucloud region' 

  --zone     string         Optional. Override default availability zone for this command
                            invocation, see 'ucloud region' 

  --project-id     string   Optional. Override default project-id for this command invocation,
                            see 'ucloud project list' 

  --yes, -y                 Optional. Do not prompt for confirmation. 

  --help, -h                help for delete 

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

