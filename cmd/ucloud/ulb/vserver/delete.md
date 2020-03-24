## ucloud ulb vserver delete

Delete ULB VServer instances

### Synopsis

Delete ULB VServer instances

```
ucloud ulb vserver delete [flags]
```

### Options

```
  --ulb-id     string        Required. Resource ID of ULB instance which the VServer to create
                             belongs to 

  --vserver-id     strings   Required. Resource ID of Vserver to update 

  --region     string        Optional. Override default region for this command invocation,
                             see 'ucloud region' 

  --project-id     string    Optional. Override default project-id for this command
                             invocation, see 'ucloud project list' 

  --help, -h                 help for delete 

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

* [ucloud ulb vserver](cli/cmd/ucloud/ulb/vserver)	 - List and manipulate ULB Vserver instances

