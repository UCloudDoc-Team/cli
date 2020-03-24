## ucloud eip list

List all EIP instances

### Synopsis

List all EIP instances

```
ucloud eip list [flags]
```

### Examples

```
ucloud eip list
```

### Options

```
  --help, -h                help for list 

  --limit     int           Optional. Limit default 50, max value 100 (default 50) 

  --offset     int          Optional. Offset default 0 

  --page-off                Optional. Paging or not. Accept values: true or false 

  --project-id     string   Optional. Override default project-id for this command invocation,
                            see 'ucloud project list' 

  --region     string       Optional. Override default region for this command invocation, see
                            'ucloud region' 

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

* [ucloud eip](cli/cmd/ucloud/eip)	 - List,allocate and release EIP

