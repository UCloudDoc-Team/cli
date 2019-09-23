{{indexmenu_n>1}}

## ucloud ulb list

List ULB instances

### Synopsis

List ULB instances

```
ucloud ulb list [flags]
```

### Options

```
  --region     string       Optional. Override default region, see 'ucloud region' 

  --project-id     string   Optional. Override default project-id, see 'ucloud project list' 

  --ulb-id     string       Optional. Resource ID of ULB instance to list 

  --vpc-id     string       Optional. Resource ID of VPC which the ULB instances to list belong to 

  --subnet-id     string    Optional. Resource ID of subnet which the ULB instances to list
                            belong to 

  --group     string        Optional. Business group of ULB instances to list 

  --offset     int          Optional. Offset 

  --limit     int           Optional. Limit (default 50) 

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

* [ucloud ulb](software/cli/cmd/ucloud/ulb)	 - List and manipulate ULB instances

