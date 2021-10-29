## ucloud firewall add-rule

Add rule to firewall instance

### Synopsis

Add rule to firewall instance

```
ucloud firewall add-rule [flags]
```

### Examples

```
ucloud firewall add-rule --fw-id firewall-2xxxxz/test.lxj2 --rules "TCP|24|0.0.0.0/0|ACCEPT|HIGH" --rules-file firewall_rules.txt
```

### Options

```
  --fw-id     strings       Required. Resource ID of firewalls to update 

  --rules     strings       Required if rules-file is empay. Rules to add to firewall.
                            Schema:'Protocol|Port|IP|Action|Level'. See 'ucloud firewall
                            create --help' for detail. 

  --rules-file     string   Required if rules is empty. Path of rules file, in which each rule
                            occupies one line. Schema: Protocol|Port|IP|Action|Level. 

  --region     string       Optional. Region, see 'ucloud region' 

  --project-id     string   Optional. Project-id, see 'ucloud project list' 

  --help, -h                help for add-rule 

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

