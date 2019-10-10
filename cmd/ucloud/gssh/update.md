{{indexmenu_n>4}}

## ucloud gssh update

Update GlobalSSH instance

### Synopsis

Update GlobalSSH instance, including port and remark attribute

```
ucloud gssh update [flags]
```

### Examples

```
ucloud gssh update --gssh-id uga-xxx --port 22
```

### Options

```
  --gssh-id     strings     Required. ResourceID of your GlobalSSH instances 

  --project-id     string   Optional. Override default project-id for this command invocation,
                            see 'ucloud project list' 

  --port     int            Optional. Port of SSH service. 

  --remark     string       Optional. Remark of your GlobalSSH. 

  --help, -h                help for update 

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

* [ucloud gssh](developer/cli/cmd/ucloud/gssh)	 - Create,list,update and delete globalssh instance

