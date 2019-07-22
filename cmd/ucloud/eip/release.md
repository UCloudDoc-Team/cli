{{indexmenu_n>3}}

## ucloud eip release

Release EIP

### Synopsis

Release EIP

```
ucloud eip release [flags]
```

### Examples

```
ucloud eip release --eip-id eip-xx1,eip-xx2
```

### Options

```
  --eip-id     strings      Required. Resource ID of the EIPs you want to release 

  --project-id     string   Optional. Override default project-id, see 'ucloud project list'
                            (default "org-oxjwoi") 

  --region     string       Optional. Override default region, see 'ucloud region' (default
                            "cn-sh2") 

  --help, -h                help for release 

```

### Options inherited from parent commands

```
  --debug, -d   Running in debug mode 

  --json, -j    Print result in JSON format whenever possible 

```

### SEE ALSO

* [ucloud eip](software/cli/cmd/ucloud/eip)	 - List,allocate and release EIP

