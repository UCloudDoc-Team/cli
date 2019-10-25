

## ucloud bw pkg create

Create bandwidth package

### Synopsis

Create bandwidth package

```
ucloud bw pkg create [flags]
```

### Examples

```
ucloud bw pkg create --eip-id eip-xxx --bandwidth-mb 20 --start-time 2018-12-15/09:20:00 --end-time 2018-12-16/09:20:00
```

### Options

```
  --eip-id     strings      Required. Resource ID of eip to be bound with created bandwidth package 

  --start-time     string   Required. The time to enable bandwidth package. Local time, for
                            example '2018-12-25/08:30:00' 

  --end-time     string     Required. The time to disable bandwidth package. Local time, for
                            example '2018-12-26/08:30:00' 

  --bandwidth-mb     int    Required. bandwidth of the bandwidth package to create.Range
                            [1,800]. Unit:'Mb'. 

  --region     string       Optional. Override default region for this command invocation, see
                            'ucloud region' 

  --project-id     string   Optional. Override default project-id for this command invocation,
                            see 'ucloud project list' 

  --help, -h                help for create 

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

* [ucloud bw pkg](developer/cli/cmd/ucloud/bw/pkg)	 - List, create and delete bandwidth package instances

