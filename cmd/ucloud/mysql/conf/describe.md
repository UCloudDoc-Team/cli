{{indexmenu_n>2}}

## ucloud mysql conf describe

Display details about a configuration file of MySQL instance

### Synopsis

Display details about a configuration file of MySQL instance

```
ucloud mysql conf describe [flags]
```

### Options

```
  --conf-id     string      Requried. Configuration identifier for the configuration to be
                            described 

  --region     string       Optional. Override default region, see 'ucloud region' (default
                            "cn-sh2") 

  --zone     string         Optional. Override default availability zone, see 'ucloud region'
                            (default "cn-sh2-02") 

  --project-id     string   Optional. Override default project-id, see 'ucloud project list'
                            (default "org-oxjwoi") 

  --help, -h                help for describe 

```

### Options inherited from parent commands

```
  --debug, -d   Running in debug mode 

  --json, -j    Print result in JSON format whenever possible 

```

### SEE ALSO

* [ucloud mysql conf](software/cli/cmd/ucloud/mysql/conf)	 - List and manipulate configuration files of MySQL instances

