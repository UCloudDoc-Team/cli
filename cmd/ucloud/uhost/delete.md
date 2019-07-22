{{indexmenu_n>3}}

## ucloud uhost delete

Delete Uhost instance

### Synopsis

Delete Uhost instance

```
ucloud uhost delete [flags]
```

### Options

```
  --uhost-id     strings    Requried. ResourceIDs(UhostIds) of the uhost instance 

  --region     string       Optional. Override default region, see 'ucloud region' (default
                            "cn-sh2") 

  --project-id     string   Optional. Override default project-id, see 'ucloud project list'
                            (default "org-oxjwoi") 

  --zone     string         Optional. availability zone 

  --destory                 Optional. false,the uhost instance will be thrown to UHost recycle
                            if you have permission; true,the uhost instance will be deleted
                            directly 

  --release-eip             Optional. false,Unbind EIP only; true, Unbind EIP and release it
                            (default true) 

  --delete-cloud-disk       Optional. false, detach cloud disk only; true, detach cloud disk
                            and delete it 

  --yes, -y                 Optional. Do not prompt for confirmation. 

  --help, -h                help for delete 

```

### Options inherited from parent commands

```
  --debug, -d   Running in debug mode 

  --json, -j    Print result in JSON format whenever possible 

```

### SEE ALSO

* [ucloud uhost](software/cli/cmd/ucloud/uhost)	 - List,create,delete,stop,restart,poweroff or resize UHost instance

