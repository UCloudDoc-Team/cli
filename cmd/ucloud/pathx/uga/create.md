## ucloud pathx uga create

Create uga instance

### Synopsis

Create uga instance

```
ucloud pathx uga create [flags]
```

### Examples

```
ucloud pathx uga create --name testcli1 --protocol tcp --origin-location 中国 --origin-domain lixiaojun.xyz --upath-id upath-auvfexxx/test_0 --port 80-90,100,110-115
```

### Options

```
  --project-id     string        Optional. Override default project-id for this command
                                 invocation, see 'ucloud project list' 

  --name     string              Required. Name of uga instance to create 

  --origin-ip     string         Required if origin-domain is empty. IP address of origin.
                                 multiple IP address separated by ',' 

  --origin-domain     string     Required if origin-ip is empty. 

  --origin-location     string   Required. Location of origin ip or domain. accpet
                                 valeus:'中国','洛杉矶','法兰克福','中国香港','雅加达','孟买','东京','莫斯科','新加坡','曼谷','中国台北','华盛顿','首尔' 

  --protocol     string          Required. accept values: tcp,udp 

  --port     strings             Required. Single port or port range, separated by ',', for
                                 example 80,3000-3010 

  --upath-id     strings         Required. Accelerated path to bind with the uga instance to
                                 create. multiple upath-id separated by ','; see 'ucloud pathx
                                 upath list 

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

* [ucloud pathx uga](developer/cli/cmd/ucloud/pathx/uga)	 - Create,list,update and delete pathx uga instances

