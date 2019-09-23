{{indexmenu_n>1}}

## ucloud vpc create

Create vpc network

### Synopsis

Create vpc network

```
ucloud vpc create [flags]
```

### Examples

```
ucloud vpc create --name xxx --segment 192.168.0.0/16
```

### Options

```
  --name     string         Required. Name of the vpc network. 

  --segment     strings     Required. The segment for private network. 

  --group     string        Optional. Business group. 

  --remark     string       Optional. The description of the vpc. 

  --region     string       Optional. Assign the region of the VPC 

  --project-id     string   Optional. Assign the project-id 

  --help, -h                help for create 

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

* [ucloud vpc](software/cli/cmd/ucloud/vpc)	 - List and manipulate VPC instances

