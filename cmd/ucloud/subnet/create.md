## ucloud subnet create

Create subnet of vpc network

### Synopsis

Create subnet of vpc network

```
ucloud subnet create [flags]
```

### Examples

```
ucloud subnet create --vpc-id uvnet-vpcxid --name testName --segment 192.168.2.0/24
```

### Options

```
  --vpc-id     string       Required. Assign the VPC network of the subnet 

  --segment     ipNet       Required. Segment of subnet. For example '192.168.0.0/24' 

  --name     string         Optional. Name of subnet to create (default "Subnet") 

  --region     string       Optional. The region of the subnet 

  --project-id     string   Optional. The project id of the subnet 

  --group     string        Optional. Business group 

  --remark     string       Optional. Remark of subnet to create 

  --help, -h                help for create 

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

* [ucloud subnet](developer/cli/cmd/ucloud/subnet)	 - List, create and delete subnet

