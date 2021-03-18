# ucloud memcache create

Create memcache instance

## Synopsis

Create memcache instance

```
ucloud memcache create [flags]
```

## Options

```
  --name     string          Required. Name of memcache instance to create 

  --size-gb     int          Optional. Memory size of memcache instance. Unit GB. Accpet
                             values:1,2,4,8,16,32 (default 1) 

  --vpc-id     string        Optional. VPC ID. See 'ucloud vpc list' 

  --subnet-id     string     Optional. Subnet ID. See 'ucloud subnet list' 

  --project-id     string    Optional. Override default project-id for this command
                             invocation, see 'ucloud project list' 

  --region     string        Optional. Override default region for this command invocation,
                             see 'ucloud region' 

  --zone     string          Optional. Override default availability zone for this command
                             invocation, see 'ucloud region' 

  --charge-type     string   Optional. Enumeration value.'Year',pay yearly;'Month',pay
                             monthly; 'Dynamic', pay hourly; 'Trial', free trial(need
                             permission) (default "Month") 

  --quantity     int         Optional. The duration of the instance. N years/months. (default 1) 

  --group     string         Optional. Business group 

  --help, -h                 help for create 

```

## Options inherited from parent commands

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

## SEE ALSO

* [ucloud memcache](cli/cmd/ucloud/memcache)	 - List and manipulate memcache instances

