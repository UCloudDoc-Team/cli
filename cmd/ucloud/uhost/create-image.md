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

  --project-id     string   Optional. Assign project-id (default "org-oxjwoi") 

  --region     string       Optional. Assign region (default "cn-sh2") 

  --zone     string         Optional. Assign availability zone (default "cn-sh2-02") 

  --async, -a               Optional. Do not wait for the long-running operation to finish. 

  --help, -h                help for create-image 

```

### Options inherited from parent commands

```
  --debug, -d   Running in debug mode 

  --json, -j    Print result in JSON format whenever possible 

```

### SEE ALSO

* [ucloud uhost](software/cli/cmd/ucloud/uhost)	 - List,create,delete,stop,restart,poweroff or resize UHost instance

