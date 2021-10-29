## ucloud pathx price list

List all the pathx acceleration area price

### Synopsis

List all the pathx acceleration area price

```
ucloud pathx price list [flags]
```

### Examples

```
ucloud pathx price list --bandwidth 10 --area-code BKK --charge-type Month
```

### Options

```
  --project-id     string    Optional. Override default project-id for this command
                             invocation, see 'ucloud project list' 

  --region     string        Optional. Override default region for this command invocation,
                             see 'ucloud region' 

  --zone     string          Optional. Override default availability zone for this command
                             invocation, see 'ucloud region' 

  --bandwidth     int        Required. The bandwidth of acceleration area to get price (default 1) 

  --area-code     string     Required. The area-code of acceleration area to get price 

  --quantity     int         Optional. When the value of the charge-type is 'Month',its
                             default value is 0,if the value of charge-type is 'Year' or
                             'Hour',its value must be greater than 0 (default 1) 

  --charge-type     string   Optional. Its value is not case sensitive,acceptable
                             values:'Year',pay yearly;'Month',pay monthly;'Hour',pay hourly 

  --accel     string         Optional. The acceleration-area to get price 

  --help, -h                 help for list 

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

* [ucloud pathx price](cli/cmd/ucloud/pathx/price)	 - List all the acceleration area price

