# ucloud gssh delete

Delete GlobalSSH instance

## Synopsis

Delete GlobalSSH instance

```
ucloud gssh delete [flags]
```

## Examples

```
ucloud gssh delete --gssh-id uga-xx1  --id uga-xx2
```

## Options

```
  --gssh-id     strings     Required. ID of the GlobalSSH instances you want to delete.
                            Multiple values specified by multiple commas 

  --project-id     string   Optional. Override default project-id for this command invocation,
                            see 'ucloud project list' 

  --help, -h                help for delete 

```

## Options inherited from parent commands

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

## SEE ALSO

* [ucloud gssh](cli/cmd/ucloud/gssh)	 - Create,list,update and delete globalssh instance

