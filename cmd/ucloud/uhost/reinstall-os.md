# ucloud uhost reinstall-os

Reinstall the operating system of the UHost instance

## Synopsis

Reinstall the operating system of the UHost instance. we will detach all udisk disks if the uhost attached some, and then stop the uhost if it's running

```
ucloud uhost reinstall-os [flags]
```

## Options

```
  --uhost-id     string     Required. Resource ID of the uhost to reinstall operating system 

  --password     string     Required. Password of the administrator 

  --image-id     string     Optional. Resource ID the image to install. See 'ucloud image
                            list'. Default is original image of the uhost 

  --project-id     string   Optional. Assign project-id 

  --region     string       Optional. Assign region 

  --zone     string         Optional. Assign availability zone 

  --keep-data-disk          Keep data disk or not. If you keep data disk, you can't change OS
                            type(Linux->Window,e.g.) 

  --yes, -y                 Optional. Do not prompt for confirmation. 

  --async, -a               Optional. Do not wait for the long-running operation to finish. 

  --help, -h                help for reinstall-os 

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

* [ucloud uhost](cli/cmd/ucloud/uhost)	 - List,create,delete,stop,restart,poweroff or resize UHost instance

