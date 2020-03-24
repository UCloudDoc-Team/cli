## ucloud uhost clone

Create an uhost with the same configuration as another uhost, excluding bound eip and udisk

### Synopsis

Create an uhost with the same configuration as another uhost, excluding bound eip and udisk

```
ucloud uhost clone [flags]
```

### Options

```
  --uhost-id     string     Required. Resource ID of the uhost to clone from 

  --password     string     Required. Password of the uhost user(root/ubuntu) 

  --name     string         Optional. Name of the uhost to clone 

  --project-id     string   Optional. Assign project-id 

  --region     string       Optional. Assign region 

  --zone     string         Optional. Assign availability zone 

  --async                   Optional. Do not wait for the long-running operation to finish. 

  --help, -h                help for clone 

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

* [ucloud uhost](cli/cmd/ucloud/uhost)	 - List,create,delete,stop,restart,poweroff or resize UHost instance

