## ucloud udisk attach

Attach udisk instances to an uhost

### Synopsis

Attach udisk instances to an uhost

```
ucloud udisk attach [flags]
```

### Examples

```
ucloud udisk attach --uhost-id uhost-xxxx --udisk-id bs-xxx1,bs-xxx2
```

### Options

```
  --uhost-id     string     Required. Resource ID of the uhost instance which you want to
                            attach the disk 

  --udisk-id     strings    Required. Resource ID of the udisk instances to attach 

  --project-id     string   Optional. Assign project-id 

  --region     string       Optional. Assign region 

  --zone     string         Optional. Assign availability zone 

  --async                   Optional. Do not wait for the long-running operation to finish. 

  --help, -h                help for attach 

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

* [ucloud udisk](developer/cli/cmd/ucloud/udisk)	 - Read and manipulate udisk instances

