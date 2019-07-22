{{indexmenu_n>4}}

## ucloud subnet list-resource

List resources belong to subnet

### Synopsis

List resources belong to subnet

```
ucloud subnet list-resource [flags]
```

### Options

```
  --subnet-id     string       Required. Resource ID of subnet which resources to list belong to 

  --resource-type     string   Optional. Resource type of resources to list. Accept
                               values:'uhost','phost','ulb','uhadoophost','ufortresshost','unatgw','ukafka','umem','docker','udb','udw' and 'vip' 

  --region     string          Optional. Override default region, see 'ucloud region' (default
                               "cn-sh2") 

  --project-id     string      Optional. Override default project-id, see 'ucloud project
                               list' (default "org-oxjwoi") 

  --limit     int              Optional. The maximum number of resources per page (default 100) 

  --offset     int             Optional. The index(a number) of resource which start to list 

  --help, -h                   help for list-resource 

```

### Options inherited from parent commands

```
  --debug, -d   Running in debug mode 

  --json, -j    Print result in JSON format whenever possible 

```

### SEE ALSO

* [ucloud subnet](software/cli/cmd/ucloud/subnet)	 - List, create and delete subnet

