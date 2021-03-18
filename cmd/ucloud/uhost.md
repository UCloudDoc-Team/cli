# ucloud uhost

List,create,delete,stop,restart,poweroff or resize UHost instance

## Synopsis

List,create,delete,stop,restart,poweroff or resize UHost instance

## Options

```
  --base-url     string       Set base-url to override the base-url in local config file 

  --help, -h                  help for uhost 

  --max-retry-times     int   Set max-retry-times to override the max-retry-times in local
                              config file (default -1) 

  --private-key     string    Set private-key to override the private-key in local config file 

  --public-key     string     Set public-key to override the public-key in local config file 

  --timeout-sec     int       Set timeout-sec to override the timeout-sec in local config file 

```

## Options inherited from parent commands

```
  --debug, -d            Running in debug mode 

  --json, -j             Print result in JSON format whenever possible 

  --profile, -p string   Specifies the configuration for the operation 

```

## SEE ALSO

* [ucloud](cli/cmd/ucloud)	 - UCloud CLI v0.1.33
* [ucloud uhost clone](cli/cmd/ucloud/uhost/clone)	 - Create an uhost with the same configuration as another uhost, excluding bound eip and udisk
* [ucloud uhost create](cli/cmd/ucloud/uhost/create)	 - Create UHost instance
* [ucloud uhost create-image](cli/cmd/ucloud/uhost/create-image)	 - Create image from an uhost instance
* [ucloud uhost delete](cli/cmd/ucloud/uhost/delete)	 - Delete Uhost instance
* [ucloud uhost isolation-group](cli/cmd/ucloud/uhost/isolation-group)	 - List and manipulate isolation group of uhost
* [ucloud uhost leave-isolation-group](cli/cmd/ucloud/uhost/leave-isolation-group)	 - Detach uhost from its isolation group
* [ucloud uhost list](cli/cmd/ucloud/uhost/list)	 - List all UHost Instances
* [ucloud uhost poweroff](cli/cmd/ucloud/uhost/poweroff)	 - Analog power off Uhost instnace
* [ucloud uhost reinstall-os](cli/cmd/ucloud/uhost/reinstall-os)	 - Reinstall the operating system of the UHost instance
* [ucloud uhost reset-password](cli/cmd/ucloud/uhost/reset-password)	 - Reset the administrator password for the UHost instances.
* [ucloud uhost resize](cli/cmd/ucloud/uhost/resize)	 - Resize uhost instance,such as cpu core count, memory size and disk size
* [ucloud uhost restart](cli/cmd/ucloud/uhost/restart)	 - Restart uhost instance
* [ucloud uhost start](cli/cmd/ucloud/uhost/start)	 - Start Uhost instance
* [ucloud uhost stop](cli/cmd/ucloud/uhost/stop)	 - Shut down uhost instance

