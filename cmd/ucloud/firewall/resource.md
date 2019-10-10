{{indexmenu_n>8}}

## ucloud firewall resource

List resources that has been applied the firewall

### Synopsis

List resources that has been applied the firewall

```
ucloud firewall resource [flags]
```

### Options

```
  --fw-id     string        Required. Resource ID of firewall 

  --region     string       Optional. Region, see 'ucloud region' 

  --project-id     string   Optional. Project-id, see 'ucloud project list' 

  --offset     string       Optional. Offset (default "0") 

  --limit     string        Optional. Limit (default "50") 

  --help, -h                help for resource 

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

* [ucloud firewall](developer/cli/cmd/ucloud/firewall)	 - List and manipulate extranet firewall

