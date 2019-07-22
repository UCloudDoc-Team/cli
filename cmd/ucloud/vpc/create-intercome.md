{{indexmenu_n>4}}

## ucloud vpc create-intercome

Create intercome with other vpc

### Synopsis

Create intercome with other vpc

```
ucloud vpc create-intercome [flags]
```

### Examples

```
ucloud vpc create-intercome --vpc-id xx --dst-vpc-id xx --dst-region xx
```

### Options

```
  --vpc-id     string           Required. The source vpc you want to establish the intercome 

  --dst-vpc-id     string       Required. The target vpc you want to establish the intercome 

  --dst-region     string       Required. If the intercome established across different
                                regions (default "cn-sh2") 

  --region     string           Optioanl. The region of source vpc which will establish the
                                intercome (default "cn-sh2") 

  --project-id     string       Optional. The project id of the source vpc (default "org-oxjwoi") 

  --dst-project-id     string   Optional. The project id of the source vpc (default "org-oxjwoi") 

  --help, -h                    help for create-intercome 

```

### Options inherited from parent commands

```
  --debug, -d   Running in debug mode 

  --json, -j    Print result in JSON format whenever possible 

```

### SEE ALSO

* [ucloud vpc](software/cli/cmd/ucloud/vpc)	 - List and manipulate VPC instances

