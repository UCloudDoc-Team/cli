{{indexmenu_n>7}}

## ucloud uhost poweroff

Analog power off Uhost instnace

### Synopsis

Analog power off Uhost instnace

```
ucloud uhost poweroff [flags]
```

### Examples

```
ucloud uhost poweroff --uhost-id uhost-xxx1,uhost-xxx2
```

### Options

```
  --uhost-id     strings    ResourceIDs(UHostIds) of the uhost instance 

  --project-id     string   Assign project-id 

  --region     string       Assign region 

  --zone     string         Assign availability zone 

  --yes, -y                 Optional. Do not prompt for confirmation. 

  --help, -h                help for poweroff 

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

* [ucloud uhost](software/cli/cmd/ucloud/uhost)	 - List,create,delete,stop,restart,poweroff or resize UHost instance

