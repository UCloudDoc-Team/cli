

## ucloud project create

Create project

### Synopsis

Create project

```
ucloud project create [flags]
```

### Examples

```
ucloud project create --name xxx
```

### Options

```
  --help, -h               help for create 

  --name     string        The name of project 

  --parent-id     string   The parent project id 

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

* [ucloud project](developer/cli/cmd/ucloud/project)	 - List,create,update and delete project

