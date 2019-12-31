## ucloud mysql db create

Create MySQL instance on UCloud platform

### Synopsis

Create MySQL instance on UCloud platform

```
ucloud mysql db create [flags]
```

### Options

```
  --project-id     string        Optional. Override default project-id for this command
                                 invocation, see 'ucloud project list' 

  --region     string            Optional. Override default region for this command
                                 invocation, see 'ucloud region' 

  --zone     string              Optional. Override default availability zone for this command
                                 invocation, see 'ucloud region' 

  --version     string           Required. Version of udb instance 

  --name     string              Required. Name of udb instance to create, at least 6 letters 

  --conf-id     string           Required. ConfID of configuration. see 'ucloud mysql conf list' 

  --admin-user-name     string   Optional. Name of udb instance's administrator (default "root") 

  --password     string          Required. Password of udb instance's administrator 

  --backup-id     int            Optional. BackupID of the backup which the newly created UDB
                                 instance will recover from if specified. See 'ucloud mysql
                                 backup list' (default -1) 

  --port     int                 Optional. Port of udb instance (default 3306) 

  --disk-type     string         Optional. Setting this flag means using SSD disk. Accept
                                 values: 'normal','sata_ssd','pcie_ssd' 

  --disk-size-gb     int         Optional. Disk size of udb instance. From 20 to 3000
                                 according to memory size. Unit GB (default 20) 

  --memory-size-gb     int       Optional. Memory size of udb instance. From 1 to 128. Unit GB
                                 (default 1) 

  --mode     string              Optional. Mode of udb instance. Normal or HA, HA means
                                 high-availability. Both the normal and high-availability
                                 versions can create master-slave synchronization for data
                                 redundancy and read/write separation. The high-availability
                                 version provides a dual-master hot standby architecture to
                                 avoid database unavailability due to downtime or hardware
                                 failure. One more thing. It does better job for master-slave
                                 synchronization and disaster recovery using the InnoDB engine
                                 (default "Normal") 

  --vpc-id     string            Optional. Resource ID of VPC which the UDB to create belong
                                 to. See 'ucloud vpc list' 

  --subnet-id     string         Optional. Resource ID of subnet that the UDB to create belong
                                 to. See 'ucloud subnet list' 

  --async                        Optional. Do not wait for the long-running operation to finish. 

  --charge-type     string       Optional. Enumeration value.'Year',pay yearly;'Month',pay
                                 monthly; 'Dynamic', pay hourly; 'Trial', free trial(need
                                 permission) (default "Month") 

  --quantity     int             Optional. The duration of the instance. N years/months.
                                 (default 1) 

  --help, -h                     help for create 

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

* [ucloud mysql db](developer/cli/cmd/ucloud/mysql/db)	 - Manange MySQL instances

