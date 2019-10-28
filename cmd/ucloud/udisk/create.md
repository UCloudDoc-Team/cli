

## ucloud udisk create

Create udisk instance

### Synopsis

Create udisk instance

```
ucloud udisk create [flags]
```

### Options

```
  --name     string              Required. Name of the udisk to create 

  --size-gb     int              Required. Size of the udisk to create. Unit:GB. Normal udisk
                                 [1,8000]; SSD udisk [1,4000]  (default 10) 

  --snapshot-id     string       Optional. Resource ID of a snapshot, which will apply to the
                                 udisk being created. If you set this option, 'udisk-type'
                                 will be omitted. 

  --project-id     string        Optional. Assign project-id 

  --region     string            Optional. Assign region 

  --zone     string              Optional. Assign availability zone 

  --charge-type     string       Optional.'Year',pay yearly;'Month',pay monthly;'Dynamic', pay
                                 hourly (default "Dynamic") 

  --quantity     int             Optional. The duration of the instance. N years/months.
                                 (default 1) 

  --enable-data-ark     string   Optional. DataArk supports real-time backup, which can
                                 restore the udisk back to any moment within the last 12
                                 hours. (default "false") 

  --group     string             Optional. Business group (default "Default") 

  --udisk-type     string        Optional. 'Ordinary' or 'SSD' (default "Oridinary") 

  --async                        Optional. Do not wait for the long-running operation to finish. 

  --count     int                Optional. The count of udisk to create. Range [1,10] (default 1) 

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

* [ucloud udisk](developer/cli/cmd/ucloud/udisk)	 - Read and manipulate udisk instances

