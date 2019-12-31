## ucloud vpc list-intercome

list intercome 

### Synopsis

list intercome

```
ucloud vpc list-intercome [flags]
```

### Examples

```
ucloud vpc list-intercome --vpc-id xx
```

### Options

```
  --help, -h                help for list-intercome 

  --project-id     string   Optional. The project id of source vpc 

  --region     string       Optional, The region of source vpc 

  --vpc-id     string       Required. The vpc id which you wnat to describe the information 

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

* [ucloud vpc](developer/cli/cmd/ucloud/vpc)	 - List and manipulate VPC instances

