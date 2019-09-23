{{indexmenu_n>4}}

## ucloud subnet list-resource

List resources belong to subnet

### Synopsis

List resources belong to subnet

```
ucloud subnet list-resource [flags]
```

### Options

```
  --subnet-id     string       Required. Resource ID of subnet which resources to list belong to 

  --resource-type     string   Optional. Resource type of resources to list. Accept
                               values:'uhost','phost','ulb','uhadoophost','ufortresshost','unatgw','ukafka','umem','docker','udb','udw' and 'vip' 

  --region     string          Optional. Override default region, see 'ucloud region' 

  --project-id     string      Optional. Override default project-id, see 'ucloud project list' 

  --limit     int              Optional. The maximum number of resources per page (default 100) 

  --offset     int             Optional. The index(a number) of resource which start to list 

  --help, -h                   help for list-resource 

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

* [ucloud subnet](software/cli/cmd/ucloud/subnet)	 - List, create and delete subnet

