{{indexmenu_n>12}}

## ucloud uhost create-image

Create image from an uhost instance

### Synopsis

Create image from an uhost instance

```
ucloud uhost create-image [flags]
```

### Options

```
  --uhost-id     string     Resource ID of uhost to create image from 

  --image-name     string   Required. Name of the image to create 

  --image-desc     string   Optional. Description of the image to create 

  --project-id     string   Optional. Assign project-id 

  --region     string       Optional. Assign region 

  --zone     string         Optional. Assign availability zone 

  --async, -a               Optional. Do not wait for the long-running operation to finish. 

  --help, -h                help for create-image 

```

### Options inherited from parent commands

```
  --base-url     string       Set base-url to override the base-url in local config file 

  --debug, -d                 Running in debug mode 

  --json, -j                  Print result in JSON format whenever possible 

  --max-retry-times     int   Set max-retry-times to override the max-retry-times in local
                              config file (default -1) 

  --private-key     string    Set private-key to override the private-key in local config file 

  --profile, -p string        Specifies the configuration for the operation 

  --public-key     string     Set public-key to override the public-key in local config file 

  --timeout-sec     int       Set timeout-sec to override the timeout-sec in local config file 

```

### SEE ALSO

* [ucloud uhost](software/cli/cmd/ucloud/uhost)	 - List,create,delete,stop,restart,poweroff or resize UHost instance

