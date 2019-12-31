## ucloud uhost create

Create UHost instance

### Synopsis

Create UHost instance

```
ucloud uhost create [flags]
```

### Options

```
  --cpu     int                          Required. The count of CPU cores. Optional
                                         parameters: {1, 2, 4, 8, 12, 16, 24, 32} (default 4) 

  --memory-gb     int                    Required. Memory size. Unit: GB. Range: [1, 128],
                                         multiple of 2 (default 8) 

  --password     string                  Required. Password of the uhost user(root/ubuntu) 

  --image-id     string                  Required. The ID of image. see 'ucloud image list' 

  --async                                Optional. Do not wait for the long-running operation
                                         to finish. 

  --count     int                        Optional. Number of uhost to create. (default 1) 

  --vpc-id     string                    Optional. VPC ID. This field is required under
                                         VPC2.0. See 'ucloud vpc list' 

  --subnet-id     string                 Optional. Subnet ID. This field is required under
                                         VPC2.0. See 'ucloud subnet list' 

  --name     string                      Optional. UHost instance name (default "UHost") 

  --bind-eip     strings                 Optional. Resource ID or IP Address of eip that will
                                         be bound to the new created uhost 

  --create-eip-line     string           Optional. BGP for regions in the chinese mainland and
                                         International for overseas regions 

  --create-eip-bandwidth-mb     int      Optional. Required if you want to create new EIP.
                                         Bandwidth(Unit:Mbps).The range of value related to
                                         network charge mode. By traffic [1, 300]; by
                                         bandwidth [1,800] (Unit: Mbps); it could be 0 if the
                                         eip belong to the shared bandwidth 

  --create-eip-traffic-mode     string   Optional. 'Traffic','Bandwidth' or 'ShareBandwidth'
                                         (default "Bandwidth") 

  --shared-bw-id     string              Optional. Resource ID of shared bandwidth. It takes
                                         effect when create-eip-traffic-mode is ShareBandwidth  

  --create-eip-name     string           Optional. Name of created eip to bind with the uhost 

  --create-eip-remark     string         Optional.Remark of your EIP. 

  --charge-type     string               Optional.'Year',pay yearly;'Month',pay
                                         monthly;'Dynamic', pay hourly (default "Month") 

  --quantity     int                     Optional. The duration of the instance. N
                                         years/months. (default 1) 

  --project-id     string                Optional. Override default project-id for this
                                         command invocation, see 'ucloud project list' 

  --region     string                    Optional. Override default region for this command
                                         invocation, see 'ucloud region' 

  --zone     string                      Optional. Override default availability zone for this
                                         command invocation, see 'ucloud region' 

  --machine-type     string              Optional. Accept values: N, C, G, O. Forward to
                                         https://docs.ucloud.cn/api/uhost-api/uhost_type for
                                         details 

  --minimal-cpu-platform     string      Optional. Accpet values: Intel/Auto, Intel/IvyBridge,
                                         Intel/Haswell, Intel/Broadwell, Intel/Skylake,
                                         Intel/Cascadelake 

  --gpu     int                          Optional. The count of GPU cores. 

  --net-capability     string            Optional. Default is 'Normal', also support 'Super'
                                         which will enhance multiple times network capability
                                         as before (default "Normal") 

  --hot-plug     string                  Optional. Enable hot plug feature or not. Accept
                                         values: true or false (default "true") 

  --os-disk-type     string              Optional. Enumeration value. 'LOCAL_NORMAL', Ordinary
                                         local disk; 'CLOUD_NORMAL', Ordinary cloud disk;
                                         'LOCAL_SSD',local ssd disk; 'CLOUD_SSD',cloud ssd
                                         disk; 'EXCLUSIVE_LOCAL_DISK',big data. The disk only
                                         supports a limited combination. (default "CLOUD_SSD") 

  --os-disk-size-gb     int              Optional. Default 20G. Windows should be bigger than
                                         40G Unit GB (default 20) 

  --os-disk-backup-type     string       Optional. Enumeration value, 'NONE' or 'DATAARK'.
                                         DataArk supports real-time backup, which can restore
                                         the disk back to any moment within the last 12 hours.
                                         (Normal Local Disk and Normal Cloud Disk Only)
                                         (default "NONE") 

  --data-disk-type     string            Optional. Enumeration value. 'LOCAL_NORMAL', Ordinary
                                         local disk; 'CLOUD_NORMAL', Ordinary cloud disk;
                                         'LOCAL_SSD',local ssd disk; 'CLOUD_SSD',cloud ssd
                                         disk; 'EXCLUSIVE_LOCAL_DISK',big data. The disk only
                                         supports a limited combination. (default "CLOUD_SSD") 

  --data-disk-size-gb     int            Optional. Disk size. Unit GB (default 20) 

  --data-disk-backup-type     string     Optional. Enumeration value, 'NONE' or 'DATAARK'.
                                         DataArk supports real-time backup, which can restore
                                         the disk back to any moment within the last 12 hours.
                                         (Normal Local Disk and Normal Cloud Disk Only)
                                         (default "NONE") 

  --firewall-id     string               Optional. Firewall Id, default: Web recommended
                                         firewall. see 'ucloud firewall list'. 

  --group     string                     Optional. Business group (default "Default") 

  --isolation-group     string           Optional. Resource ID of isolation group. see 'ucloud
                                         uhost isolation-group list 

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

* [ucloud uhost](developer/cli/cmd/ucloud/uhost)	 - List,create,delete,stop,restart,poweroff or resize UHost instance

