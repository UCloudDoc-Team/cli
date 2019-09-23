{{indexmenu_n>3}}

## ucloud ulb vserver backend update

Update attributes of ULB backend nodes

### Synopsis

Update attributes of ULB backend nodes

```
ucloud ulb vserver backend update [flags]
```

### Options

```
  --ulb-id     string         Required. Resource ID of ULB which the backend nodes belong to 

  --backend-id     strings    Required. BackendID of backend nodes to update 

  --port     int              Optional. Port of your real server listening on backend nodes to
                              update. Rnage [1,65535] 

  --backend-mode     string   Optional. Enable backend node or not. Accept values: enable, disable 

  --weight     int            Optional. effective for lb-method WeightRoundrobin. Rnage
                              [0,100], -1 meaning no update (default -1) 

  --region     string         Optional. Override default region, see 'ucloud region' 

  --project-id     string     Optional. Override default project-id, see 'ucloud project list' 

  --help, -h                  help for update 

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

* [ucloud ulb vserver backend](software/cli/cmd/ucloud/ulb/vserver/backend)	 - List and manipulate VServer backend nodes

