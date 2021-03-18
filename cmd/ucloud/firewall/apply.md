# ucloud firewall apply

Applay firewall to ucloud service

## Synopsis

Applay firewall to ucloud service

```
ucloud firewall apply [flags]
```

## Examples

```
ucloud firewall apply --fw-id firewall-xxx --resource-id uhost-xxx --resource-type uhost
```

## Options

```
  --fw-id     string           Required. Resource ID of firewall to apply to some ucloud resource 

  --resource-type     string   Required. Resource type of resource to be applied firewall.
                               Range
                               'uhost','unatgw','upm','hadoophost','fortresshost','udhost','udockhost','dbaudit'. 

  --resource-id     strings    Resource ID of resources to be applied firewall 

  --region     string          Optional. Region, see 'ucloud region' 

  --project-id     string      Optional. Project-id, see 'ucloud project list' 

  --help, -h                   help for apply 

```

## Options inherited from parent commands

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

## SEE ALSO

* [ucloud firewall](cli/cmd/ucloud/firewall)	 - List and manipulate extranet firewall

