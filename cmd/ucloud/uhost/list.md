## ucloud uhost list

List all UHost Instances

### Synopsis

List all UHost Instances

```
ucloud uhost list [flags]
```

### Options

```
  --project-id     string        Optional. Assign project-id 

  --region     string            Optional. Assign region. 

  --zone     string              Optional. Assign availability zone 

  --offset     int               Optional. Offset default 0 

  --limit     int                Optional. Limit default 50, max value 100 (default 50) 

  --vpc-id     string            Optional. Resource ID of VPC. List uhost instances of the
                                 specified VPC 

  --subnet-id     string         Optional. Resource ID of Subnet. List uhost instances of the
                                 specified Subnet 

  --isolation-group     string   Optional. Resource ID of isolation group. List uhost
                                 instances of the specified isolation group 

  --uhost-id     strings         Optional. Resource ID of uhost instances, multiple values
                                 separated by comma(without space) 

  --all-region                   Optional. Accpet values: true or false. List uhost instances
                                 of all regions when assigned true 

  --page-off                     Optional. Paging or not. If all-region is specified this flag
                                 will be true. Accept values: true or false. If assigned, the
                                 limit flag will be disabled and list all uhost instances 

  --uhost-id-only                Optional. Just display resource id of uhost 

  --output, -o string            Optional. Accept values: wide. Display more information about
                                 uhost such as DiskSet and Zone 

  --group     string             Optional. Business group 

  --help, -h                     help for list 

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

* [ucloud uhost](cli/cmd/ucloud/uhost)	 - List,create,delete,stop,restart,poweroff or resize UHost instance

