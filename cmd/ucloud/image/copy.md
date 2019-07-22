{{indexmenu_n>2}}

## ucloud image copy

Copy custom images

### Synopsis

Copy custom images

```
ucloud image copy [flags]
```

### Options

```
  --source-image-id     strings    Required. Resource ID of source image 

  --project-id     string          Optional. Assign project-id (default "org-oxjwoi") 

  --region     string              Optional. Assign region (default "cn-sh2") 

  --zone     string                Optional. Assign availability zone (default "cn-sh2-02") 

  --target-region     string       Optional. Target region. See 'ucloud region' (default "cn-sh2") 

  --target-project     string      Optional. Target Project ID. See 'ucloud project list'
                                   (default "org-oxjwoi") 

  --target-image-name     string   Optional. Name of target image 

  --target-image-desc     string   Optional. Description of target image 

  --async                          Optional. Do not wait for the long-running operation to finish. 

  --help, -h                       help for copy 

```

### Options inherited from parent commands

```
  --debug, -d   Running in debug mode 

  --json, -j    Print result in JSON format whenever possible 

```

### SEE ALSO

* [ucloud image](software/cli/cmd/ucloud/image)	 - List and manipulate images

