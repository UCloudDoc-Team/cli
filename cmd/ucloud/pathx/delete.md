## ucloud pathx delete

Delete the pathx resource and port

### Synopsis

Delete the pathx resource and port

```
ucloud pathx delete [flags]
```

### Examples

```
ucloud pathx delete --id uga3-xxx
```

### Options

```
  --id     string           Required. It is the resource ID of pathx, and the deletion will be
                            performed according to this 

  --project-id     string   Optional. Override default project-id for this command invocation,
                            see 'ucloud project list' 

  --region     string       Optional. Override default region for this command invocation, see
                            'ucloud region' 

  --zone     string         Optional. Override default availability zone for this command
                            invocation, see 'ucloud region' 

  --yes, -y                 Optional. Do not prompt for confirmation. 

  --help, -h                help for delete 

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

* [ucloud pathx](cli/cmd/ucloud/pathx)	 - Manipulate uga and upath instances

