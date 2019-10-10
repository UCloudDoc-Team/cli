{{indexmenu_n>7}}

## ucloud firewall delete

Delete firewall by resource ids or names

### Synopsis

Delete firewall by resource ids or names

```
ucloud firewall delete [flags]
```

### Examples

```
ucloud firewall delete --fw-id firewall-xxx
```

### Options

```
  --fw-id     strings       Required. Resource IDs of firewall to delete 

  --region     string       Optional. Region, see 'ucloud region' 

  --project-id     string   Optional. Project-id, see 'ucloud project list' 

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

* [ucloud firewall](developer/cli/cmd/ucloud/firewall)	 - List and manipulate extranet firewall

