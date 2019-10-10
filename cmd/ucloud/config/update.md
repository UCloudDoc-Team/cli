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
  --public-key     string         Required. Set public key 

  --private-key     string        Required. Set private key 

  --region     string             Optional. Set default region. For instance 'cn-bj2' See
                                  'ucloud region' 

  --zone     string               Optional. Set default zone. For instance 'cn-bj2-02'. See
                                  'ucloud region' 

  --project-id     string         Optional. Set default project. For instance 'org-xxxxxx'.
                                  See 'ucloud project list 

  --base-url     string           Optional. Set default base url. For instance
                                  'https://api.ucloud.cn/' 

  --timeout-sec     string        Optional. Set default timeout for requesting API. Unit: seconds 

  --max-retry-times     string    Optional. Set default max retry times for idempotent APIs
                                  which can be called many times without side effect, for
                                  example 'ReleaseEIP' 

  --active     string             Optional. Mark the profile to be effective 

  --agree-upload-log     string   Optional. Agree to upload log in local file
                                  ~/.ucloud/cli.log or not. Accept valeus: true or false 

  --help, -h                      help for update 

```

### Options inherited from parent commands

```
  --debug, -d            Running in debug mode 

  --json, -j             Print result in JSON format whenever possible 

  --profile, -p string   Specifies the configuration for the operation 

```

### SEE ALSO

* [ucloud config](developer/cli/cmd/ucloud/config)	 - add or update configurations

