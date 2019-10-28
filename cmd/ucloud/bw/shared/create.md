

## ucloud bw shared create

Create shared bandwidth instance

### Synopsis

Create shared bandwidth instance

```
ucloud bw shared create [flags]
```

### Options

```
  --name     string          Required. Name of the shared bandwidth instance 

  --bandwidth-mb     int     Optional. Unit:Mb. Bandwidth of the shared bandwidth. Range
                             [20,5000] (default 20) 

  --region     string        Optional. Override default region for this command invocation,
                             see 'ucloud region' 

  --project-id     string    Optional. Override default project-id for this command
                             invocation, see 'ucloud project list' 

  --charge-type     string   Optional.'Year',pay yearly;'Month',pay monthly;'Dynamic', pay
                             hourly (default "Month") 

  --quantity     int         Optional. The duration of the instance. N years/months. (default 1) 

  --help, -h                 help for create 

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

* [ucloud bw shared](developer/cli/cmd/ucloud/bw/shared)	 - Create and manipulate shared bandwidth instances

