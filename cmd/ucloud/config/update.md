{{indexmenu_n>2}}

## ucloud config update

update configurations

### Synopsis

update configurations

```
ucloud config update [flags]
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

  --base-url     string      Optional. Set default base url. For instance 'https://api.ucloud.cn/' 

  --timeout-sec     string   Optional. Set default timeout for requesting API. Unit: seconds 

  --active     string        Optional. Mark the profile to be effective 

  --help, -h                 help for update 

```

### Options inherited from parent commands

```
  --debug, -d   Running in debug mode 

  --json, -j    Print result in JSON format whenever possible 

```

### SEE ALSO

* [ucloud config](software/cli/cmd/ucloud/config)	 - add or update configurations

