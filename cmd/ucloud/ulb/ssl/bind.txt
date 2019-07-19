{{indexmenu_n>5}}

====== bind ======

## ucloud ulb ssl bind

Bind SSL Certificate with VServer

### Synopsis

Bind SSL Certificate with VServer

```
ucloud ulb ssl bind [flags]
```

### Options

```
  --region     string       Optional. Override default region, see 'ucloud region' (default
                            "cn-bj2") 

  --project-id     string   Optional. Override default project-id, see 'ucloud project list'
                            (default "org-ryrmms") 

  --ssl-id     string       Required. Resource ID of SSL Certificate to bind 

  --ulb-id     string       Required. Resource ID of ULB 

  --vserver-id     string   Required. Resource ID of VServer 

  --help, -h                help for bind 

```

### Options inherited from parent commands

```
  --debug, -d   Running in debug mode 

  --json, -j    Print result in JSON format whenever possible 

```

### SEE ALSO

* [ucloud ulb ssl](software/cli/cmd/ucloud/ulb/ssl)	 - List and manipulate SSL Certificates for ULB

