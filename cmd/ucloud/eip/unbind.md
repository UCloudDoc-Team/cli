{{indexmenu_n>5}}

====== unbind ======

## ucloud eip unbind

Unbind EIP with uhost

### Synopsis

Unbind EIP with uhost

```
ucloud eip unbind [flags]
```

### Examples

```
ucloud eip unbind --eip-id eip-xxx
```

### Options

```
  --eip-id     strings      Required. Resource ID of eips to unbind with some resource 

  --region     string       Optional. Override default region, see 'ucloud region' (default
                            "cn-bj2") 

  --project-id     string   Optional. Override default project-id, see 'ucloud project list'
                            (default "org-ryrmms") 

  --help, -h                help for unbind 

```

### Options inherited from parent commands

```
  --debug, -d   Running in debug mode 

  --json, -j    Print result in JSON format whenever possible 

```

### SEE ALSO

* [ucloud eip](software/cli/cmd/ucloud/eip)	 - List,allocate and release EIP

