{{indexmenu_n>9}}

## ucloud eip leave-shared-bw

Leave shared bandwidth

### Synopsis

Leave shared bandwidth

```
ucloud eip leave-shared-bw [flags]
```

### Examples

```
ucloud eip leave-shared-bw --eip-id eip-b2gvu3
```

### Options

```
  --eip-id     strings        Required. Resource ID of EIPs to leave shared bandwidth 

  --bandwidth-mb     int      Required. Bandwidth of EIP after leaving shared bandwidth,
                              ranging [1,300] for 'Traffic' charge mode, ranging [1,800] for
                              'Bandwidth' charge mode. Unit:Mb (default 1) 

  --traffic-mode     string   Optional. Charge mode of the EIP after leaving shared bandwidth,
                              'Bandwidth' or 'Traffic' (default "Bandwidth") 

  --shared-bw-id     string   Optional. Resource ID of shared bandwidth instance, assign this
                              flag to make the operation faster 

  --region     string         Optional. Region, see 'ucloud region' 

  --project-id     string     Optional. Project-id, see 'ucloud project list' 

  --help, -h                  help for leave-shared-bw 

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

* [ucloud eip](developer/cli/cmd/ucloud/eip)	 - List,allocate and release EIP

