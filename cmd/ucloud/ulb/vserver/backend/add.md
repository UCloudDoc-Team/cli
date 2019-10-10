{{indexmenu_n>2}}

## ucloud ulb vserver backend add

Add backend nodes for ULB Vserver instance

### Synopsis

Add backend nodes for ULB Vserver instance

```
ucloud ulb vserver backend add [flags]
```

### Options

```
  --ulb-id     string          Required. Resource ID of ULB which the backend nodes belong to 

  --vserver-id     string      Required. Resource ID of VServer which the backend nodes belong to 

  --resource-id     strings    Required. Resource ID of the backend nodes to add 

  --region     string          Optional. Override default region for this command invocation,
                               see 'ucloud region' 

  --project-id     string      Optional. Override default project-id for this command
                               invocation, see 'ucloud project list' 

  --resource-type     string   Optional. Resource type of the backend node to add. Accept
                               values: UHost,UPM,UDHost,UDocker (default "UHost") 

  --port     int               Optional. The port of your real server on the backend node
                               listening on (default 80) 

  --backend-mode     string    Optional. Enable backend node or not. Accept values: enable,
                               disable (default "enable") 

  --weight     int             Optional. effective for lb-method WeightRoundrobin. Rnage
                               [0,100] (default 1) 

  --help, -h                   help for add 

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

* [ucloud ulb vserver backend](developer/cli/cmd/ucloud/ulb/vserver/backend)	 - List and manipulate VServer backend nodes

