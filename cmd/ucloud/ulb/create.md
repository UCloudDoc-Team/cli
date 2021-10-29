## ucloud ulb create

Create ULB instance

### Synopsis

Create ULB instance

```
ucloud ulb create [flags]
```

### Options

```
  --name     string                      Required. Name of ULB instance to create 

  --mode     string                      Required. Network mode of ULB instance, outer or
                                         inner. (default "outer") 

  --region     string                    Optional. Override default region for this command
                                         invocation, see 'ucloud region' 

  --project-id     string                Optional. Override default project-id for this
                                         command invocation, see 'ucloud project list' 

  --vpc-id     string                    Optional. Resource ID of VPC which the ULB to create
                                         belong to. See 'ucloud vpc list' 

  --subnet-id     string                 Optional. Resource ID of subnet. This flag will be
                                         discarded when you are creating an outter mode ULB.
                                         See 'ucloud subnet list' 

  --charge-type     string               Optional.'Year',pay yearly;'Month',pay
                                         monthly;'Dynamic', pay hourly (default "Month") 

  --group     string                     Optional. Business group (default "Default") 

  --remark     string                    Optional. Remark of instance to create. 

  --bind-eip     string                  Optional. Resource ID or IP Address of eip that will
                                         be bound to the new created outer mode ulb 

  --create-eip-bandwidth-mb     int      Optional. Required if you want to create new EIP.
                                         Bandwidth(Unit:Mbps).The range of value related to
                                         network charge mode. By traffic [1, 300]; by
                                         bandwidth [1,800] (Unit: Mbps); it could be 0 if the
                                         eip belong to the shared bandwidth 

  --create-eip-line     string           Optional. Line of created eip to bind with the new
                                         created outer mode ulb 

  --create-eip-traffic-mode     string   Optional. 'Traffic','Bandwidth' or 'ShareBandwidth'
                                         (default "Bandwidth") 

  --create-eip-name     string           Optional. Name of created eip to bind with the new
                                         created outer mode ulb 

  --create-eip-remark     string         Optional. Remark of your EIP. 

  --help, -h                             help for create 

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

* [ucloud ulb](cli/cmd/ucloud/ulb)	 - List and manipulate ULB instances

