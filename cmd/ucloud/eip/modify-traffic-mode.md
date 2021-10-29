## ucloud eip modify-traffic-mode

Modify charge mode of EIP instances

### Synopsis

Modify charge mode of EIP instances

```
ucloud eip modify-traffic-mode [flags]
```

### Examples

```
ucloud eip modify-traffic-mode --eip-id eip-xx1,eip-xx2 --traffic-mode Traffic
```

### Options

```
  --eip-id     strings        Required, Resource ID of EIPs to modify charge mode 

  --traffic-mode     string   Required, Charge mode of eip, 'Traffic','Bandwidth' or
                              'PostAccurateBandwidth' 

  --project-id     string     Optional. Assign project-id 

  --region     string         Optional. Assign region 

  --help, -h                  help for modify-traffic-mode 

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

* [ucloud eip](cli/cmd/ucloud/eip)	 - List,allocate and release EIP

