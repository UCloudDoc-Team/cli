## ucloud ulb vserver policy add

Add content forward policy for VServer

### Synopsis

Add content forward policy for VServer

```
ucloud ulb vserver policy add [flags]
```

### Options

```
  --ulb-id     string           Required. Resource ID of ULB 

  --vserver-id     string       Required. Resource ID of VServer 

  --backend-id     strings      Required. BackendID of the VServer's backend nodes 

  --forward-method     string   Required. Forward method, accept values:Domain and Path; Both
                                forwarding methods can be described by using regular
                                expressions or wildcards 

  --expression     string       Required. Expression of domain or path, such as
                                "www.[123].demo.com" or "/path/img/*.jpg" 

  --region     string           Optional. Override default region for this command invocation,
                                see 'ucloud region' 

  --project-id     string       Optional. Override default project-id for this command
                                invocation, see 'ucloud project list' 

  --help, -h                    help for add 

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

* [ucloud ulb vserver policy](developer/cli/cmd/ucloud/ulb/vserver/policy)	 - List and manipulate forward policy for VServer

