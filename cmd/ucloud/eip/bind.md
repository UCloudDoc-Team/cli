

## ucloud eip bind

Bind EIP with uhost

### Synopsis

Bind EIP with uhost

```
ucloud eip bind [flags]
```

### Examples

```
ucloud eip bind --eip-id eip-xxx --resource-id uhost-xxx
```

### Options

```
  --eip-id     strings         Required. EIPId to bind 

  --resource-id     string     Required. ResourceID , which is the UHostId of uhost 

  --resource-type     string   Requried. ResourceType, type of resource to bind with eip.
                               'uhost','vrouter','ulb','upm','hadoophost'.eg.. (default "uhost") 

  --project-id     string      Optional. Assign project-id 

  --region     string          Optional. Assign region 

  --help, -h                   help for bind 

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

* [ucloud eip](developer/cli/cmd/ucloud/eip)	 - List,allocate and release EIP

