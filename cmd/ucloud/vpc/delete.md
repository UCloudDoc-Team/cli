{{indexmenu_n>3}}

## ucloud vpc delete

Delete vpc network

### Synopsis

Delete vpc network

```
ucloud vpc delete [flags]
```

### Examples

```
ucloud vpc delete --vpc-id uvnet-xxx
```

### Options

```
  --vpc-id     strings      Required. Resource ID of the vpc network to delete 

  --region     string       Optional. Region of the vpc (default "cn-sh2") 

  --project-id     string   Optional. Project id of the vpc (default "org-oxjwoi") 

  --help, -h                help for delete 

```

### Options inherited from parent commands

```
  --debug, -d   Running in debug mode 

  --json, -j    Print result in JSON format whenever possible 

```

### SEE ALSO

* [ucloud vpc](software/cli/cmd/ucloud/vpc)	 - List and manipulate VPC instances

