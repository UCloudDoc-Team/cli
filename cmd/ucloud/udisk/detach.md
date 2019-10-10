{{indexmenu_n>4}}

## ucloud udisk detach

Detach udisk instances from an uhost

### Synopsis

Detach udisk instances from an uhost

```
ucloud udisk detach [flags]
```

### Options

```
  --udisk-id     strings    Required. Resource ID of the udisk instances to detach 

  --project-id     string   Optional. Assign project-id 

  --region     string       Optional. Assign region 

  --zone     string         Optional. Assign availability zone 

  --async, -a               Optional. Do not wait for the long-running operation to finish. 

  --yes, -y                 Optional. Do not prompt for confirmation. 

  --help, -h                help for detach 

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

* [ucloud udisk](developer/cli/cmd/ucloud/udisk)	 - Read and manipulate udisk instances

