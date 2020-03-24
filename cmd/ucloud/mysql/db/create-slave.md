## ucloud mysql db create-slave

Create slave database

### Synopsis

Create slave database

```
ucloud mysql db create-slave [flags]
```

### Options

```
  --master-udb-id     string   Required. Resource ID of master UDB instance 

  --name     string            Required. Name of the slave DB to create 

  --port     int               Optional. Port of the slave db service (default 3306) 

  --region     string          Optional. Override default region for this command invocation,
                               see 'ucloud region' 

  --zone     string            Optional. Override default availability zone for this command
                               invocation, see 'ucloud region' 

  --project-id     string      Optional. Override default project-id for this command
                               invocation, see 'ucloud project list' 

  --disk-type     string       Optional. Setting this flag means using SSD disk. Accept
                               values: normal, sata_ssd, pcie_ssd (default "Normal") 

  --memory-size-gb     int     Optional. Memory size of udb instance. From 1 to 128. Unit GB
                               (default 1) 

  --async                      Optional. Do not wait for the long-running operation to finish 

  --is-lock                    Optional. Lock master DB or not 

  --help, -h                   help for create-slave 

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

* [ucloud mysql db](cli/cmd/ucloud/mysql/db)	 - Manange MySQL instances

