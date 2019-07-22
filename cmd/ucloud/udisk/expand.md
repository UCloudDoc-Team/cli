{{indexmenu_n>7}}

## ucloud udisk expand

Expand udisk size

### Synopsis

Expand udisk size

```
ucloud udisk expand [flags]
```

### Options

```
  --udisk-id     strings    Required. Resource ID of the udisks to expand 

  --size-gb     int         Required. Size of the udisk after expanded. Unit: GB. Range [1,8000] 

  --project-id     string   Optional. Assign project-id (default "org-oxjwoi") 

  --region     string       Optional. Assign region (default "cn-sh2") 

  --zone     string         Optional. Assign availability zone (default "cn-sh2-02") 

  --help, -h                help for expand 

```

### Options inherited from parent commands

```
  --debug, -d   Running in debug mode 

  --json, -j    Print result in JSON format whenever possible 

```

### SEE ALSO

* [ucloud udisk](software/cli/cmd/ucloud/udisk)	 - Read and manipulate udisk instances

