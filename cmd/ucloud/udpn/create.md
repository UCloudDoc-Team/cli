{{indexmenu_n>1}}

## ucloud udpn create

Create UDPN tunnel

### Synopsis

Create UDPN tunnel

```
ucloud udpn create [flags]
```

### Options

```
  --peer1     string         Required. One end of the tunnel to create 

  --peer2     string         Required. The other end of the tunnel create 

  --bandwidth-mb     int     Required. Bandwidth of the tunnel to create. Unit:Mb. Rnange [2,1000] 

  --charge-type     string   Optional. Enumeration value.'Year',pay yearly;'Month',pay
                             monthly;'Dynamic', pay hourly 

  --quantity     int         Optional. The duration of the instance. N years/months. (default 1) 

  --project-id     string    Optional. Project-id, see 'ucloud project list' 

  --help, -h                 help for create 

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

* [ucloud udpn](developer/cli/cmd/ucloud/udpn)	 - List and manipulate udpn instances

