{{indexmenu_n>6}}

## ucloud firewall copy

Copy firewall

### Synopsis

Copy firewall

```
ucloud firewall copy [flags]
```

### Examples

```
ucloud firewall copy --src-fw firewall-xxx --target-region cn-bj2 --name test
```

### Options

```
  --src-fw     string          Required. ResourceID or name of source firewall 

  --name     string            Required. Name of new firewall 

  --region     string          Optional. Current region, used to fetch source firewall 

  --target-region     string   Optional. Copy firewall to target region 

  --project-id     string      Optional. Project-id, see 'ucloud project list' 

  --help, -h                   help for copy 

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

* [ucloud firewall](software/cli/cmd/ucloud/firewall)	 - List and manipulate extranet firewall

