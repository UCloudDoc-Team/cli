{{indexmenu_n>5}}

## ucloud eip unbind

Unbind EIP with uhost

### Synopsis

Unbind EIP with uhost

```
ucloud eip unbind [flags]
```

### Examples

```
ucloud eip unbind --eip-id eip-xxx
```

### Options

```
  --eip-id     strings      Required. Resource ID of eips to unbind with some resource 

  --region     string       Optional. Override default region, see 'ucloud region' 

  --project-id     string   Optional. Override default project-id, see 'ucloud project list' 

  --help, -h                help for unbind 

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

* [ucloud eip](software/cli/cmd/ucloud/eip)	 - List,allocate and release EIP

