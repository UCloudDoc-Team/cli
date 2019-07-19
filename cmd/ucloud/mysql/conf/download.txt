{{indexmenu_n>8}}

====== download ======

## ucloud mysql conf download

Download UDB configuration

### Synopsis

Download UDB configuration

```
ucloud mysql conf download [flags]
```

### Options

```
  --conf-id     string      Required. ConfID of configuration to download 

  --region     string       Optional. Override default region, see 'ucloud region' (default
                            "cn-bj2") 

  --zone     string         Optional. Override default availability zone, see 'ucloud region'
                            (default "cn-bj2-02") 

  --project-id     string   Optional. Override default project-id, see 'ucloud project list'
                            (default "org-ryrmms") 

  --help, -h                help for download 

```

### Options inherited from parent commands

```
  --debug, -d   Running in debug mode 

  --json, -j    Print result in JSON format whenever possible 

```

### SEE ALSO

* [ucloud mysql conf](software/cli/cmd/ucloud/mysql/conf)	 - List and manipulate configuration files of MySQL instances

