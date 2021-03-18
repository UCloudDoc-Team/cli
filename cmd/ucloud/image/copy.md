# ucloud image copy

Copy custom images

## Synopsis

Copy custom images

```
ucloud image copy [flags]
```

## Options

```
  --source-image-id     strings    Required. Resource ID of source image 

  --project-id     string          Optional. Assign project-id 

  --region     string              Optional. Assign region 

  --zone     string                Optional. Assign availability zone 

  --target-region     string       Optional. Target region. See 'ucloud region' 

  --target-project     string      Optional. Target Project ID. See 'ucloud project list' 

  --target-image-name     string   Optional. Name of target image 

  --target-image-desc     string   Optional. Description of target image 

  --async                          Optional. Do not wait for the long-running operation to finish. 

  --help, -h                       help for copy 

```

## Options inherited from parent commands

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

## SEE ALSO

* [ucloud image](cli/cmd/ucloud/image)	 - List and manipulate images

