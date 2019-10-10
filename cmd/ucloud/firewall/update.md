{{indexmenu_n>9}}

## ucloud firewall update

Update firewall attribute, such as name,group and remark.

### Synopsis

Update firewall attribute, such as name,group and remark.

```
ucloud firewall update [flags]
```

### Examples

```
ucloud firewall update --fw-id firewall-2xxxx/test2 --name test_update.1 --remark "this is a remark"
```

### Options

```
  --fw-id     strings       Required. Resource ID of firewalls 

  --region     string       Optional. Region, see 'ucloud region' 

  --project-id     string   Optional. Project-id, see 'ucloud project list' 

  --name     string         Name of firewall 

  --group     string        Group of firewall 

  --remark     string       Remark of firewall 

  --help, -h                help for update 

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

