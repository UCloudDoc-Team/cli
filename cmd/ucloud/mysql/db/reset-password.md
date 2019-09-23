{{indexmenu_n>9}}

## ucloud mysql db reset-password

Reset password of MySQL instances

### Synopsis

Reset password of MySQL instances

```
ucloud mysql db reset-password [flags]
```

### Options

```
  --udb-id     strings      Required. Resource ID of UDB instances to reset password 

  --password     string     Required. New password 

  --project-id     string   Optional. Override default project-id, see 'ucloud project list' 

  --region     string       Optional. Override default region, see 'ucloud region' 

  --zone     string         Optional. Override default availability zone, see 'ucloud region' 

  --help, -h                help for reset-password 

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

* [ucloud mysql db](software/cli/cmd/ucloud/mysql/db)	 - Manange MySQL instances

