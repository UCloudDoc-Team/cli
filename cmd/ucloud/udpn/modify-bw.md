{{indexmenu_n>4}}

## ucloud udpn modify-bw

Modify bandwidth of UDPN tunnel

### Synopsis

Modify bandwidth of UDPN tunnel

```
ucloud udpn modify-bw [flags]
```

### Options

```
  --udpn-id     strings     Required. Resource ID of UDPN to modify bandwidth 

  --bandwidth-mb     int    Required. Bandwidth of UDPN tunnel. Unit:Mb. Range [2,1000] 

  --region     string       Optional. Region, see 'ucloud region' (default "cn-sh2") 

  --project-id     string   Optional. Project-id, see 'ucloud project list' (default "org-oxjwoi") 

  --help, -h                help for modify-bw 

```

### Options inherited from parent commands

```
  --debug, -d   Running in debug mode 

  --json, -j    Print result in JSON format whenever possible 

```

### SEE ALSO

* [ucloud udpn](software/cli/cmd/ucloud/udpn)	 - List and manipulate udpn instances

