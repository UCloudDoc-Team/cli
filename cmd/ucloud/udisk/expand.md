## ucloud udisk expand

Expand udisk size

### Synopsis

Expand udisk size

```
ucloud udisk expand [flags]
```

### Options

```
  --udisk-id     strings    Required. Resource ID of the udisks to expand 

  --size-gb     int         Required. Size of the udisk after expanded. Unit: GB. Range [1,8000] 

  --project-id     string   Optional. Assign project-id 

  --region     string       Optional. Assign region 

  --zone     string         Optional. Assign availability zone 

  --help, -h                help for expand 

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

* [ucloud udisk](cli/cmd/ucloud/udisk)	 - Read and manipulate udisk instances

