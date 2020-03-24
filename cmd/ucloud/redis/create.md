## ucloud redis create

Create redis instance

### Synopsis

Create redis instance

```
ucloud redis create [flags]
```

### Options

```
  --name     string          Required. Name of the redis to create. Range of the password
                             length is [6,63] and the password can only contain letters and numbers 

  --type     string          Required. Type of the redis. Accept
                             values:'master-replica','distributed' 

  --size-gb     int          Optional. Memory size. Default value 1GB(for master-replica redis
                             type) or 16GB(for distributed redis type). Unit GB (default 1) 

  --version     string       Optional. Version of redis (default "3.2") 

  --vpc-id     string        Optional. VPC ID. This field is required under VPC2.0. See
                             'ucloud vpc list' 

  --subnet-id     string     Optional. Subnet ID. This field is required under VPC2.0. See
                             'ucloud subnet list' 

  --password     string      Optional. Password of redis to create 

  --region     string        Optional. Override default region for this command invocation,
                             see 'ucloud region' 

  --zone     string          Optional. Override default availability zone for this command
                             invocation, see 'ucloud region' 

  --project-id     string    Optional. Override default project-id for this command
                             invocation, see 'ucloud project list' 

  --group     string         Optional. Business group 

  --charge-type     string   Optional. Enumeration value.'Year',pay yearly;'Month',pay
                             monthly; 'Dynamic', pay hourly; 'Trial', free trial(need
                             permission) (default "Month") 

  --quantity     int         Optional. The duration of the instance. N years/months. (default 1) 

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

* [ucloud redis](cli/cmd/ucloud/redis)	 - List and manipulate redis instances

