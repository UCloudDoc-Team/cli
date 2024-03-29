## ucloud vpc delete

Delete vpc network

### Synopsis

Delete vpc network

```
ucloud vpc delete [flags]
```

### Examples

```
ucloud vpc delete --vpc-id uvnet-xxx
```

### Options

```
  --vpc-id     strings      Required. Resource ID of the vpc network to delete 

  --region     string       Optional. Region of the vpc 

  --project-id     string   Optional. Project id of the vpc 

  --help, -h                help for delete 

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

* [ucloud vpc](cli/cmd/ucloud/vpc)	 - List and manipulate VPC instances

