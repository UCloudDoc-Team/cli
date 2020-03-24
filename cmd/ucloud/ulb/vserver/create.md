## ucloud ulb vserver create

Create ULB VServer instance

### Synopsis

Create ULB VServer instance

```
ucloud ulb vserver create [flags]
```

### Options

```
  --ulb-id     string                  Required. Resource ID of ULB instance which the VServer
                                       to create belongs to 

  --region     string                  Optional. Override default region for this command
                                       invocation, see 'ucloud region' 

  --project-id     string              Optional. Override default project-id for this command
                                       invocation, see 'ucloud project list' 

  --name     string                    Optional. Name of VServer to create 

  --listen-type     string             Optional. Listen type, 'RequestProxy' or
                                       'PacketsTransmit' (default "RequestProxy") 

  --protocol     string                Optional. Protocol of VServer instance,
                                       'HTTP','HTTPS','TCP' for listen type 'RequestProxy' and
                                       'TCP','UDP' for listen type 'PacketsTransmit' (default
                                       "HTTP") 

  --port     int                       Optional. Port of VServer instance (default 80) 

  --ssl-id     string                  Optional. Required if you choose HTTPS, Resource ID of
                                       SSL Certificate 

  --lb-method     string               Optional. LB methods, accept
                                       values:Roundrobin,Source,ConsistentHash,SourcePort,ConsistentHashPort,WeightRoundrobin and Leastconn. 
                                       ConsistentHash,SourcePort and ConsistentHashPort are effective for listen type PacketsTransmit only;
                                       Leastconn is effective for listen type RequestProxy only;
                                       Roundrobin,Source and WeightRoundrobin are effective for both listen types (default "Roundrobin") 

  --session-maintain-mode     string   Optional. The method of maintaining user's session.
                                       Accept values: 'None','ServerInsert' and 'UserDefined'.
                                       'None' meaning don't maintain user's session';
                                       'ServerInsert' meaning auto create session key;
                                       'UserDefined' meaning specify session key which
                                       accpeted by flag seesion-maintain-key by yourself
                                       (default "None") 

  --session-maintain-key     string    Optional. Specify a key for maintaining session 

  --client-timeout-seconds     int     Optional.Unit seconds. For 'RequestProxy', it's
                                       lifetime for idle connections, range (0，86400]. For
                                       'PacketsTransmit', it's the duration of the connection
                                       is maintained, range [60，900] (default 60) 

  --health-check-mode     string       Optional. Method of checking real server's status of
                                       health. Accept values:'Port','Path' (default "Port") 

  --health-check-domain     string     Optional. Skip this flag if health-check-mode is
                                       assigned Port 

  --health-check-path     string       Optional. Skip this flags if health-check-mode is
                                       assigned Port 

  --help, -h                           help for create 

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

* [ucloud ulb vserver](cli/cmd/ucloud/ulb/vserver)	 - List and manipulate ULB Vserver instances

