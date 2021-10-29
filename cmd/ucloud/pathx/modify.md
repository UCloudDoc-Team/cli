## ucloud pathx modify

Modify the pathx associated information. Example bandwidth or origin information or resource information

### Synopsis

Support modify bandwidth,origin information,resource information,port

```
ucloud pathx modify [flags]
```

### Examples

```
ucloud pathx modify --id uga3-xxx --bandwidth 1 --origin-ip 127.0.0.1 --name Pathx测试 --remark 加速资源 --protocol TCP --port 30010 --origin-port 39999
```

### Options

```
  --project-id     string      Optional. Override default project-id for this command
                               invocation, see 'ucloud project list' 

  --region     string          Optional. Override default region for this command invocation,
                               see 'ucloud region' 

  --zone     string            Optional. Override default availability zone for this command
                               invocation, see 'ucloud region' 

  --id     string              Required. It is the resource ID of the pathx 

  --bandwidth     int          Optional. The bandwidth size. Its value range [1-100],no update
                               if no value is specified 

  --origin-ip     string       Optional. Acceleration source IP. If multiple values
                               exist,please split by ',' 

  --origin-domain     string   Optional. Acceleration source domain name. Only 1 domain is
                               supported 

  --name     string            Optional. Accelerate configuration resource name. If its value
                               is not filled in or an empty string is not updated 

  --remark     string          Optional. It will be modified if its value is not empty 

  --port     strings           Optional. Disable 65123 port,the port can be multiple,please
                               split by ',' for example 80,3000-3010. The number of port must
                               be consistent with the number of origin-port,and the number
                               cannot greater than or equals to 10 

  --origin-port     strings    Optional. The origin-port can be multiple,please split by ','
                               for example 80,3000-3010.The number of origin-port must be
                               consistent with the number of port 

  --protocol     string        Its values can be TCP and UDP, but currently only supports TCP
                               (default "TCP") 

  --help, -h                   help for modify 

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

* [ucloud pathx](cli/cmd/ucloud/pathx)	 - Manipulate uga and upath instances

