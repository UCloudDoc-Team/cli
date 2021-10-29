## ucloud pathx area list

List origin area or acceleration area information

### Synopsis

Provide optional flags to get the optional list of global access source stations

```
ucloud pathx area list [flags]
```

### Examples

```
ucloud pathx area list --origin-ip 0.0.0.0 --origin-domain test.com
```

### Options

```
  --project-id     string      Optional. Override default project-id for this command
                               invocation, see 'ucloud project list' 

  --region     string          Optional. Override default region for this command invocation,
                               see 'ucloud region' 

  --zone     string            Optional. Override default availability zone for this command
                               invocation, see 'ucloud region' 

  --time-range     string      Optional. The default value is 1 day. Acceptable
                               values:'Hour','Day','Week',and its value is not case sensitive 

  --accel     string           Optional. The acceleration area,acceptable
                               values:'Global','AP','EU','ME','OA','AF','NA','SA' 

  --origin-domain     string   Optional. If you fill in the IP or domain name, a region will
                               be recommended as the first in the return list 

  --origin-ip     string       Optional. If you fill in the IP or domain name, a region will
                               be recommended as the first IP collection of the source station
                               in the return list, split by ',' example:110.10.10.1,111.100.0.10  

  --no-accel                   Optional. If it is specified,the print result will not be
                               displayed acceleration areas 

  --help, -h                   help for list 

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

* [ucloud pathx area](cli/cmd/ucloud/pathx/area)	 - List origin area or acceleration area information

