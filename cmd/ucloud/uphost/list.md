{{indexmenu_n>1}}

## ucloud uphost list

List UPHost instances

### Synopsis

List UPHost instances

```
ucloud uphost list [flags]
```

### Options

```
  --help, -h                help for list 

  --limit     int           Optional. The maximum number of resources per page (default 100) 

  --offset     int          Optional. The index(a number) of resource which start to list 

  --project-id     string   Optional. Override default project-id, see 'ucloud project list' 

  --region     string       Optional. Override default region, see 'ucloud region' 

  --uphost-id     strings   Optional. Resource ID of uphost instances. List those specified
                            uphost instances 

  --zone     string         Optional. Override default availability zone, see 'ucloud region' 

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

* [ucloud uphost](software/cli/cmd/ucloud/uphost)	 - List UPHost instances

