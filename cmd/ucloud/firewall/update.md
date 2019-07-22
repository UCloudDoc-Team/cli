{{indexmenu_n>9}}

## ucloud firewall update

Update firewall attribute, such as name,group and remark.

### Synopsis

Update firewall attribute, such as name,group and remark.

```
ucloud firewall update [flags]
```

### Examples

```
ucloud firewall update --fw-id firewall-2xxxx/test2 --name test_update.1 --remark "this is a remark"
```

### Options

```
  --fw-id     strings       Required. Resource ID of firewalls 

  --region     string       Optional. Region, see 'ucloud region' (default "cn-sh2") 

  --project-id     string   Optional. Project-id, see 'ucloud project list' (default "org-oxjwoi") 

  --name     string         Name of firewall 

  --group     string        Group of firewall 

  --remark     string       Remark of firewall 

  --help, -h                help for update 

```

### Options inherited from parent commands

```
  --debug, -d   Running in debug mode 

  --json, -j    Print result in JSON format whenever possible 

```

### SEE ALSO

* [ucloud firewall](software/cli/cmd/ucloud/firewall)	 - List and manipulate extranet firewall

