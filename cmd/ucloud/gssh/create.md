# ucloud gssh create

Create GlobalSSH instance

## Synopsis

Create GlobalSSH instance

```
ucloud gssh create [flags]
```

## Examples

```
ucloud gssh create --location Washington --target-ip 8.8.8.8
```

## Options

```
  --location     string      Required. Location of the source server. See 'ucloud gssh location' 

  --target-ip     ip         Required. IP of the source server. Required 

  --project-id     string    Optional. Override default project-id for this command
                             invocation, see 'ucloud project list' 

  --port     int             Optional. Port of The SSH service between 1 and 65535. Do not use
                             ports such as 80,443. (default 22) 

  --remark     string        Optional. Remark of your GlobalSSH. 

  --charge-type     string   Optional.'Year',pay yearly;'Month',pay monthly;'Dynamic', pay
                             hourly(requires access) (default "Month") 

  --quantity     int         Optional. The duration of the instance. N years/months. (default 1) 

  --help, -h                 help for create 

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

