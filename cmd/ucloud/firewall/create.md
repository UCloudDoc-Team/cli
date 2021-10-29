## ucloud firewall create

Create firewall

### Synopsis

Create firewall

```
ucloud firewall create [flags]
```

### Examples

```
ucloud firewall create --name test3 --rules "TCP|22|0.0.0.0/0|ACCEPT|HIGH" --rules-file firewall_rules.txt
```

### Options

```
  --rules     strings       Required if rules-file doesn't exist. Schema:
                            Protocol|Port|IP|Action|Level. Prototol range 'TCP','UDP','ICMP'
                            and 'GRE'; Port is a local port accessed by source address, port
                            range [0-65535]; IP is the source address of the network packet
                            that requests ucloud host resource, supporting IP address and
                            network segment, such as '120.132.69.216' or '0.0.0.0/0'; Action
                            is the processing behavior of the packet when the firewall is in
                            effect, including 'ACCEPT' AND 'DROP'; Level, when a rule is added
                            to a firewall, the rules take effect in order of level, which
                            range 'HIGH','MEDIUM' and 'LOW'. For example,
                            'TCP|22|192.168.1.1/22|DROP|LOW' 

  --rules-file     string   Required if rules doesn't exist. Path of rules file, in which each
                            rule occupies one line. Schema: Protocol|Port|IP|Action|Level. 

  --name     string         Required. Name of firewall to create 

  --region     string       Optional. Region, see 'ucloud region' 

  --project-id     string   Optional. Project-id, see 'ucloud project list' 

  --group     string        Optional. Group of the firewall to create 

  --remark     string       Optional. Remark of the firewall to create 

  --help, -h                help for create 

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

* [ucloud firewall](cli/cmd/ucloud/firewall)	 - List and manipulate extranet firewall

