{{indexmenu_n>1}}

## ucloud image list

List image

### Synopsis

List image

```
ucloud image list [flags]
```

### Examples

```
ucloud image list --image-type Base
```

### Options

```
  --help, -h                help for list 

  --image-id     string     Optional. Resource ID of image 

  --image-type     string   Optional. 'Base',Standard image; 'Business',image market;
                            'Custom',custom image (default "Base") 

  --limit     int           Optional. Max count (default 500) 

  --offset     int          Optional. Offset default 0 

  --os-type     string      Optional. Linux or Windows. Return all types by default 

  --project-id     string   Optional. Assign project-id 

  --region     string       Optional. Assign region 

  --zone     string         Optional. Assign availability zone 

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

* [ucloud image](software/cli/cmd/ucloud/image)	 - List and manipulate images

