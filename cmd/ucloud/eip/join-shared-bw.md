{{indexmenu_n>8}}

## ucloud eip join-shared-bw

Join shared bandwidth

### Synopsis

Join shared bandwidth

```
ucloud eip join-shared-bw [flags]
```

### Examples

```
ucloud eip join-shared-bw --eip-id eip-xxx --shared-bw-id bwshare-xxx
```

### Options

```
  --eip-id     strings        Required. Resource ID of EIPs to join shared bandwdith 

  --shared-bw-id     string   Required. Resource ID of shared bandwidth to be joined 

  --region     string         Optional. Region, see 'ucloud region' (default "cn-sh2") 

  --project-id     string     Optional. Project-id, see 'ucloud project list' (default
                              "org-oxjwoi") 

  --help, -h                  help for join-shared-bw 

```

### Options inherited from parent commands

```
  --debug, -d   Running in debug mode 

  --json, -j    Print result in JSON format whenever possible 

```

### SEE ALSO

* [ucloud eip](software/cli/cmd/ucloud/eip)	 - List,allocate and release EIP

