{{indexmenu_n>6}}

## ucloud uhost restart

Restart uhost instance

### Synopsis

Restart uhost instance

```
ucloud uhost restart [flags]
```

### Examples

```
ucloud uhost restart --uhost-id uhost-xxx1,uhost-xxx2
```

### Options

```
  --uhost-id     strings       Required. ResourceIDs(UHostIds) of the uhost instance 

  --project-id     string      Optional. Assign project-id 

  --region     string          Optional. Assign region 

  --zone     string            Optional. Assign availability zone 

  --disk-password     string   Optional. Encrypted disk password 

  --async                      Optional. Do not wait for the long-running operation to finish. 

  --help, -h                   help for restart 

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

