## ucloud mysql logs archive

Archive the log of mysql as a compressed file

### Synopsis

Archive the log of mysql as a compressed file

```
ucloud mysql logs archive [flags]
```

### Examples

```
ucloud mysql logs archive --name test.cli2 --udb-id udb-xxx/test.cli1 --log-type slow_query --begin-time 2019-02-23/15:30:00 --end-time 2019-02-24/15:31:00
```

### Options

```
  --udb-id     string       Required. Resource ID of UDB instance which we fetch logs from 

  --name     string         Required. Name of compressed file 

  --log-type     string     Required. Type of log to package. Accept values: slow_query, error 

  --begin-time     string   Optional. Required when log-type is slow. For example
                            2019-01-02/15:04:05 

  --end-time     string     Optional. Required when log-type is slow. For example
                            2019-01-02/15:04:05 

  --region     string       Optional. Override default region for this command invocation, see
                            'ucloud region' 

  --zone     string         Optional. Override default availability zone for this command
                            invocation, see 'ucloud region' 

  --project-id     string   Optional. Override default project-id for this command invocation,
                            see 'ucloud project list' 

  --help, -h                help for archive 

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

* [ucloud mysql logs](developer/cli/cmd/ucloud/mysql/logs)	 - List and manipulate logs of MySQL instance

