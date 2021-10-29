## ucloud uhost resize

Resize uhost instance,such as cpu core count, memory size and disk size

### Synopsis

Resize uhost instance,such as cpu core count, memory size and disk size

```
ucloud uhost resize [flags]
```

### Examples

```
ucloud uhost resize --uhost-id uhost-xxx1,uhost-xxx2 --cpu 4 --memory-gb 8
```

### Options

```
  --uhost-id     strings          Required. ResourceIDs(or UhostIDs) of the uhost instances 

  --project-id     string         Optional. Override default project-id for this command
                                  invocation, see 'ucloud project list' 

  --region     string             Optional. Override default region for this command
                                  invocation, see 'ucloud region' 

  --zone     string               Optional. Override default availability zone for this
                                  command invocation, see 'ucloud region' 

  --cpu     int                   Optional. The number of virtual CPU cores. Series1 {1, 2, 4,
                                  8, 12, 16, 24, 32}. Series2 {1,2,4,8,16} 

  --memory-gb     int             Optional. memory size. Unit: GB. Range: [1, 128], multiple of 2 

  --system-disk-size-gb     int   Optional. System disk size, unit GB. Range[20,100]. Step 10.
                                  System disk does not support shrinkage 

  --data-disk-size-gb     int     Optional. Data disk size,unit GB. Step 10. disk does not
                                  support shrinkage 

  --data-disk-id     string       Optional. If the uhost specified has two or more data disks,
                                  this parameter should be assigned 

  --net-cap     int               Optional. NIC scale. 1,upgrade; 2,downgrade; 0,unchanged 

  --yes, -y                       Optional. Do not prompt for confirmation. 

  --async, -a                     Optional. Do not wait for the long-running operation to finish. 

  --help, -h                      help for resize 

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

* [ucloud uhost](cli/cmd/ucloud/uhost)	 - List,create,delete,stop,restart,poweroff or resize UHost instance

