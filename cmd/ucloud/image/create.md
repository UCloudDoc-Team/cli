{{indexmenu_n>4}}

## ucloud image create

Create image from an uhost instance

### Synopsis

Create image from an uhost instance

```
ucloud image create [flags]
```

### Options

```
  --uhost-id     string     Resource ID of uhost to create image from 

  --image-name     string   Required. Name of the image to create 

  --image-desc     string   Optional. Description of the image to create 

  --project-id     string   Optional. Assign project-id (default "org-oxjwoi") 

  --region     string       Optional. Assign region (default "cn-sh2") 

  --zone     string         Optional. Assign availability zone (default "cn-sh2-02") 

  --async, -a               Optional. Do not wait for the long-running operation to finish. 

  --help, -h                help for create 

```

### Options inherited from parent commands

```
  --debug, -d   Running in debug mode 

  --json, -j    Print result in JSON format whenever possible 

```

### SEE ALSO

* [ucloud image](software/cli/cmd/ucloud/image)	 - List and manipulate images

