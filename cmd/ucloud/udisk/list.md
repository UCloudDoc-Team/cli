{{indexmenu_n>2}}

## ucloud udisk list

List udisk instance

### Synopsis

List udisk instance

```
ucloud udisk list [flags]
```

### Options

```
  --project-id     string   Optional. Assign project-id (default "org-oxjwoi") 

  --region     string       Optional. Assign region (default "cn-sh2") 

  --zone     string         Optional. Assign availability zone (default "cn-sh2-02") 

  --udisk-id     string     Optional. Resource ID of the udisk to search 

  --udisk-type     string   Optional. Optional. Type of the udisk to search.
                            'Oridinary-Data-Disk','Oridinary-System-Disk' or 'SSD-Data-Disk' 

  --offset     int          Optional. Offset 

  --limit     int           Optional. Limit (default 50) 

  --help, -h                help for list 

```

### Options inherited from parent commands

```
  --debug, -d   Running in debug mode 

  --json, -j    Print result in JSON format whenever possible 

```

### SEE ALSO

* [ucloud udisk](software/cli/cmd/ucloud/udisk)	 - Read and manipulate udisk instances

