{{indexmenu_n>8}}

## ucloud eip join-shared-bw

Join shared bandwidth

### Synopsis

Join shared bandwidth

```
ucloud eip join-shared-bw [flags]
```

### Examples

```
ucloud eip join-shared-bw --eip-id eip-xxx --shared-bw-id bwshare-xxx
```

### Options

```
  --eip-id     strings        Required. Resource ID of EIPs to join shared bandwdith 

  --shared-bw-id     string   Required. Resource ID of shared bandwidth to be joined 

  --region     string         Optional. Region, see 'ucloud region' 

  --project-id     string     Optional. Project-id, see 'ucloud project list' 

  --help, -h                  help for join-shared-bw 

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

