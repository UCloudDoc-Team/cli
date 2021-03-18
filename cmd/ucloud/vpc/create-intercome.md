# ucloud vpc create-intercome

Create intercome with other vpc

## Synopsis

Create intercome with other vpc

```
ucloud vpc create-intercome [flags]
```

## Examples

```
ucloud vpc create-intercome --vpc-id xx --dst-vpc-id xx --dst-region xx
```

## Options

```
  --vpc-id     string           Required. The source vpc you want to establish the intercome 

  --dst-vpc-id     string       Required. The target vpc you want to establish the intercome 

  --dst-region     string       Required. If the intercome established across different regions 

  --region     string           Optioanl. The region of source vpc which will establish the
                                intercome 

  --project-id     string       Optional. The project id of the source vpc 

  --dst-project-id     string   Optional. The project id of the source vpc 

  --help, -h                    help for create-intercome 

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

* [ucloud vpc](cli/cmd/ucloud/vpc)	 - List and manipulate VPC instances

