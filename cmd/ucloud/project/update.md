

## ucloud project update

Update project name

### Synopsis

Update project name

```
ucloud project update [flags]
```

### Examples

```
ucloud project update --id org-xxx --name new_name
```

### Options

```
  --help, -h          help for update 

  --id     string     The project id 

  --name     string   The new name of project 

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

