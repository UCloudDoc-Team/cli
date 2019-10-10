{{indexmenu_n>1}}

## ucloud ext uhost switch-eip

Switch EIP for UHost instances

### Synopsis

Switch EIP for UHost instances

```
ucloud ext uhost switch-eip [flags]
```

### Examples

```
ucloud ext uhost switch-eip --uhost-id uhost-1n1sxx2,uhost-li4jxx1 --create-eip-bandwidth-mb 2
```

### Options

```
  --uhost-id     strings                       Required. Resource ID of uhost instances to
                                               switch EIP 

  --eip-addr     strings                       Optional. Address of EIP instances to be
                                               replaced. if eip-id is empty, replace all of
                                               the EIPs bound with the uhost  

  --unbind-all                                 Optional. Unbind all EIP instances that has
                                               been replaced. Accept values:true or false
                                               (default true) 

  --release-all                                Optional. Release all EIP instances that has
                                               been replaced. Accept values:true or false
                                               (default true) 

  --create-eip-bandwidth-mb     int            Optional. Bandwidth of EIP instance to be
                                               create with. Unit:Mb (default 1) 

  --create-eip-traffic-mode     string         Optional. traffic-mode is an enumeration value.
                                               'Traffic','Bandwidth' or 'ShareBandwidth'
                                               (default "Bandwidth") 

  --create-eip-share-bandwidth-id     string   Optional. ShareBandwidthId, required only when
                                               traffic-mode is 'ShareBandwidth' 

  --create-eip-charge-type     string          Optional. Enumeration value.'Year',pay
                                               yearly;'Month',pay monthly;'Dynamic', pay
                                               hourly (default "Month") 

  --create-eip-quantity     int                Optional. The duration of the instance. N
                                               years/months. (default 1) 

  --project-id     string                      Optional. Override default project-id for this
                                               command invocation, see 'ucloud project list' 

  --region     string                          Optional. Override default region for this
                                               command invocation, see 'ucloud region' 

  --zone     string                            Optional. Override default availability zone
                                               for this command invocation, see 'ucloud region' 

  --help, -h                                   help for switch-eip 

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

* [ucloud ext uhost](developer/cli/cmd/ucloud/ext/uhost)	 - extended uhost commands

