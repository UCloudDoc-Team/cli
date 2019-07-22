{{indexmenu_n>1}}

## ucloud config add

add configuration

### Synopsis

add configuration

```
ucloud config add [flags]
```

### Options

```
  --profile     string       Required. Set name of CLI profile 

  --public-key     string    Required. Set public key 

  --private-key     string   Required. Set private key 

  --region     string        Optional. Set default region. For instance 'cn-bj2' See 'ucloud
                             region' 

  --zone     string          Optional. Set default zone. For instance 'cn-bj2-02'. See 'ucloud
                             region' 

  --project-id     string    Optional. Set default project. For instance 'org-xxxxxx'. See
                             'ucloud project list 

  --base-url     string      Optional. Set default base url. For instance
                             'https://api.ucloud.cn/' (default "https://api.ucloud.cn/") 

  --timeout-sec     int      Optional. Set default timeout for requesting API. Unit: seconds
                             (default 15) 

  --active     string        Optional. Mark the profile to be effective or not. Accept valeus:
                             true or false (default "false") 

  --help, -h                 help for add 

```

### Options inherited from parent commands

```
  --debug, -d   Running in debug mode 

  --json, -j    Print result in JSON format whenever possible 

```

### SEE ALSO

* [ucloud config](software/cli/cmd/ucloud/config)	 - add or update configurations

