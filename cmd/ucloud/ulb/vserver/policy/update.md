{{indexmenu_n>3}}

## ucloud ulb vserver policy update

Update content forward policies of ULB VServer

### Synopsis

Update content forward policies ULB VServer

```
ucloud ulb vserver policy update [flags]
```

### Options

```
  --region     string               Optional. Override default region for this command
                                    invocation, see 'ucloud region' 

  --project-id     string           Optional. Override default project-id for this command
                                    invocation, see 'ucloud project list' 

  --ulb-id     string               Required. Resource ID of ULB 

  --vserver-id     string           Required. Resource ID of VServer 

  --policy-id     strings           Required. PolicyID of policies to update 

  --backend-id     strings          Optional. BackendID of backend nodes. If assign this flag,
                                    it will rewrite all backend nodes of the policy 

  --add-backend-id     strings      Optional. BackendID of backend nodes. Add backend nodes to
                                    the policy 

  --remove-backend-id     strings   Optional. BackendID of backend nodes. Remove those backend
                                    nodes from the policy 

  --forward-method     string       Optional. Forward method of policy, accept values:Domain
                                    and Path 

  --expression     string           Optional. Expression of domain or path, such as
                                    "www.[123].demo.com" or "/path/img/*.jpg" 

  --help, -h                        help for update 

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

