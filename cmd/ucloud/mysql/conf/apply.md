## ucloud mysql conf apply

Apply configuration for UDB instances

### Synopsis

Apply configuration for UDB instances

```
ucloud mysql conf apply [flags]
```

### Options

```
  --conf-id     string        Required. ConfID of the configuration to be applied 

  --udb-id     strings        Required. Resource ID of UDB instances to change configuration 

  --restart-after-apply       Optional. The new configuration will take effect after DB
                              restarts (default true) 

  --yes, -y                   Optional. Do not prompt for confirmation 

  --async, -a                 Optional. Do not wait for the long-running operation to finish. 

  --region     string         Optional. Override default region for this command invocation,
                              see 'ucloud region' 

  --zone     string           Optional. Override default availability zone for this command
                              invocation, see 'ucloud region' 

  --project-id     string     Optional. Override default project-id for this command
                              invocation, see 'ucloud project list' 

  --help, -h                  help for apply 

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

* [ucloud mysql conf](developer/cli/cmd/ucloud/mysql/conf)	 - List and manipulate configuration files of MySQL instances

