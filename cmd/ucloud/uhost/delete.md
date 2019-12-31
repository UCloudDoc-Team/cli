## ucloud uhost delete

Delete Uhost instance

### Synopsis

Delete Uhost instance

```
ucloud uhost delete [flags]
```

### Options

```
  --uhost-id     strings    Requried. ResourceIDs(UhostIds) of the uhost instance 

  --region     string       Optional. Override default region for this command invocation, see
                            'ucloud region' 

  --project-id     string   Optional. Override default project-id for this command invocation,
                            see 'ucloud project list' 

  --zone     string         Optional. availability zone 

  --destroy                 Optional. false,the uhost instance will be thrown to UHost recycle
                            if you have permission; true,the uhost instance will be deleted
                            directly 

  --release-eip             Optional. false,Unbind EIP only; true, Unbind EIP and release it
                            (default true) 

  --delete-cloud-disk       Optional. false, detach cloud disk only; true, detach cloud disk
                            and delete it (default true) 

  --yes, -y                 Optional. Do not prompt for confirmation. 

  --help, -h                help for delete 

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

