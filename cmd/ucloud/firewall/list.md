

## ucloud firewall list

List extranet firewall

### Synopsis

List extranet firewall

```
ucloud firewall list [flags]
```

### Options

```
  --region     string                Optional. Region, see 'ucloud region' 

  --project-id     string            Optional. Project-id, see 'ucloud project list' 

  --firewall-id     string           Optional. The Rsource ID of firewall. Return all
                                     firewalls by default. 

  --bound-resource-type     string   Optional. The type of resource bound on the firewall 

  --bound-resource-id     string     Optional. The resource ID of resource bound on the firewall 

  --offset     int                   Optional. Offset 

  --limit     int                    Optional. Limit (default 50) 

  --help, -h                         help for list 

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

