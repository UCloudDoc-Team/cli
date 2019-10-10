{{indexmenu_n>3}}

## ucloud config

add or update configurations

### Synopsis

add or update configurations, such as private-key, public-key, default region and zone, base-url, timeout-sec, and default project-id

```
ucloud config [flags]
```

### Examples

```
ucloud config --profile=test --region cn-bj2 --active true
```

### Options

```
  --public-key     string         Optional. Set public key 

  --private-key     string        Optional. Set private key 

  --region     string             Optional. Set default region. For instance 'cn-bj2' See
                                  'ucloud region' 

  --zone     string               Optional. Set default zone. For instance 'cn-bj2-02'. See
                                  'ucloud region' 

  --project-id     string         Optional. Set default project. For instance 'org-xxxxxx'.
                                  See 'ucloud project list 

  --base-url     string           Optional. Set default base url. For instance
                                  'https://api.ucloud.cn/' 

  --timeout-sec     int           Optional. Set default timeout for requesting API. Unit: seconds 

  --max-retry-times     int       Optional. Set default max-retry-times for idempotent APIs
                                  which can be called many times without side effect, for
                                  example 'ReleaseEIP' 

  --active     string             Optional. Mark the profile to be effective or not. Accept
                                  valeus: true or false 

  --agree-upload-log     string   Optional. Agree to upload log in local file
                                  ~/.ucloud/cli.log or not. Accept valeus: true or false
                                  (default "false") 

  --help, -h                      help for config 

```

### Options inherited from parent commands

```
  --debug, -d            Running in debug mode 

  --json, -j             Print result in JSON format whenever possible 

  --profile, -p string   Specifies the configuration for the operation 

```

### SEE ALSO

* [ucloud](developer/cli/cmd/ucloud)	 - UCloud CLI v0.1.25
* [ucloud config add](developer/cli/cmd/ucloud/config/add)	 - add configuration
* [ucloud config delete](developer/cli/cmd/ucloud/config/delete)	 - delete configurations by profile name
* [ucloud config list](developer/cli/cmd/ucloud/config/list)	 - list all configurations
* [ucloud config update](developer/cli/cmd/ucloud/config/update)	 - update configurations

