{{indexmenu_n>4}}

## ucloud mysql conf upload

Create configuration file by uploading local DB configuration file

### Synopsis

Create configuration file by uploading local DB configuration file

```
ucloud mysql conf upload [flags]
```

### Options

```
  --conf-file     string     Required. Path of local configuration file 

  --db-version     string    Required. Version of DB. Accept values:mysql-5.1, mysql-5.5,
                             mysql-5.6, mysql-5.7, percona-5.5, percona-5.6, percona-5.7,
                             mariadb-10.0 

  --name     string          Required. Name of configuration. It's length should be between 6
                             and 63 

  --description     string   Optional. Description of the configuration to clone (default " ") 

  --region     string        Optional. Override default region for this command invocation,
                             see 'ucloud region' 

  --zone     string          Optional. Override default availability zone for this command
                             invocation, see 'ucloud region' 

  --project-id     string    Optional. Override default project-id for this command
                             invocation, see 'ucloud project list' 

  --help, -h                 help for upload 

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

* [ucloud mysql conf](developer/cli/cmd/ucloud/mysql/conf)	 - List and manipulate configuration files of MySQL instances

