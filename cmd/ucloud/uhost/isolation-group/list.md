## ucloud uhost isolation-group list

List isolation group of uhost

### Synopsis

List isolation group of uhost

```
ucloud uhost isolation-group list [flags]
```

### Options

```
  --group-id     string     Optional. Resource ID of isolation group to describe 

  --region     string       Optional. Override default region for this command invocation, see
                            'ucloud region' 

  --project-id     string   Optional. Override default project-id for this command invocation,
                            see 'ucloud project list' 

  --limit     int           Optional. The maximum number of resources per page (default 100) 

  --offset     int          Optional. The index(a number) of resource which start to list 

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

* [ucloud uhost isolation-group](cli/cmd/ucloud/uhost/isolation-group)	 - List and manipulate isolation group of uhost

