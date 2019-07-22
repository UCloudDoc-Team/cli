{{indexmenu_n>3}}

## ucloud pathx uga create

Create uga instance

### Synopsis

Create uga instance

```
ucloud pathx uga create [flags]
```

### Examples

```
ucloud pathx uga create --name testcli1 --protocol tcp --origin-location 中国 --origin-domain lixiaojun.xyz --upath-id upath-auvfexxx/test_0 --port 80-90,100,110-115
```

### Options

```
  --project-id     string        Optional. Override default project-id, see 'ucloud project
                                 list' (default "org-oxjwoi") 

  --name     string              Required. Name of uga instance to create 

  --origin-ip     string         Required if origin-domain is empty. IP address of origin.
                                 multiple IP address separated by ',' 

  --origin-domain     string     Required if origin-ip is empty. 

  --origin-location     string   Required. Location of origin ip or domain. accpet
                                 valeus:'中国','洛杉矶','法兰克福','中国香港','雅加达','孟买','东京','莫斯科','新加坡','曼谷','中国台北','华盛顿','首尔' 

  --protocol     string          Required. accept values: tcp,udp 

  --port     strings             Required. Single port or port range, separated by ',', for
                                 example 80,3000-3010 

  --upath-id     strings         Required. Accelerated path to bind with the uga instance to
                                 create. multiple upath-id separated by ','; see 'ucloud pathx
                                 upath list 

  --help, -h                     help for create 

```

### Options inherited from parent commands

```
  --debug, -d   Running in debug mode 

  --json, -j    Print result in JSON format whenever possible 

```

### SEE ALSO

* [ucloud pathx uga](software/cli/cmd/ucloud/pathx/uga)	 - Create,list,update and delete pathx uga instances

