## ucloud memcache list

List memcache instances

### Synopsis

List memcache instances

```
ucloud memcache list [flags]
```

### Options

```
  --umem-id     string      Optional. Resource ID of the redis to list 

  --region     string       Optional. Override default region for this command invocation, see
                            'ucloud region' 

  --zone     string         Optional. Override default availability zone for this command
                            invocation, see 'ucloud region' 

  --project-id     string   Optional. Override default project-id for this command invocation,
                            see 'ucloud project list' 

  --offset     int          Optional. The index(a number) of resource which start to list 

  --limit     int           Optional. The maximum number of resources per page (default 100) 

  --help, -h                help for list 

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

* [ucloud memcache](cli/cmd/ucloud/memcache)	 - List and manipulate memcache instances

