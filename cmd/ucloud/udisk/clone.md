{{indexmenu_n>6}}

## ucloud udisk clone

Clone an udisk

### Synopsis

Clone an udisk

```
ucloud udisk clone [flags]
```

### Options

```
  --source-id     string         Required. Resource ID of parent udisk 

  --name     string              Required. Name of new udisk 

  --project-id     string        Optional. Assign project-id 

  --region     string            Optional. Assign region 

  --zone     string              Optional. Assign availability zone 

  --charge-type     string       Optional.'Year',pay yearly;'Month',pay monthly;'Dynamic', pay
                                 hourly (default "Month") 

  --quantity     int             Optional. The duration of the instance. N years/months.
                                 (default 1) 

  --enable-data-ark     string   Optional. DataArk supports real-time backup, which can
                                 restore the udisk back to any moment within the last 12
                                 hours. (default "false") 

  --coupon-id     string         Optional. Coupon ID, The Coupon can deduct part of the
                                 payment,see https://accountv2.ucloud.cn 

  --async                        Optional. Do not wait for the long-running operation to finish. 

  --help, -h                     help for clone 

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

* [ucloud udisk](software/cli/cmd/ucloud/udisk)	 - Read and manipulate udisk instances

