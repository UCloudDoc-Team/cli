## ucloud mysql db resize

Reszie MySQL instances, such as memory size, disk size and disk type

### Synopsis

Reszie MySQL instances, such as memory size, disk size and disk type

```
ucloud mysql db resize [flags]
```

### Options

```
  --udb-id     strings        Required. Resource ID of UDB instances to restart 

  --region     string         Optional. Override default region for this command invocation,
                              see 'ucloud region' 

  --zone     string           Optional. Override default availability zone for this command
                              invocation, see 'ucloud region' 

  --project-id     string     Optional. Override default project-id for this command
                              invocation, see 'ucloud project list' 

  --memory-size-gb     int    Optional. Memory size of udb instance. From 1 to 128. Unit GB 

  --disk-size-gb     int      Optional. Disk size of udb instance. From 20 to 3000 according
                              to memory size. Unit GB. Step 10GB 

  --disk-type     string      Optional. Disk type of udb instance. Accept values:normal,
                              sata_ssd, pcie_ssd, normal_volume, sata_ssd_volume, pcie_ssd_volume 

  --start-after-upgrade       Optional. Automatic start the UDB instances after upgrade
                              (default true) 

  --async, -a                 Optional. Do not wait for the long-running operation to finish 

  --yes, -y                   Optional. Do not prompt for confirmation 

  --help, -h                  help for resize 

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

