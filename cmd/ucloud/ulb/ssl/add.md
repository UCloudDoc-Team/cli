{{indexmenu_n>3}}

## ucloud ulb ssl add

Add SSL Certificate

### Synopsis

Add SSL Certificate

```
ucloud ulb ssl add [flags]
```

### Options

```
  --region     string                  Optional. Override default region for this command
                                       invocation, see 'ucloud region' 

  --project-id     string              Optional. Override default project-id for this command
                                       invocation, see 'ucloud project list' 

  --name     string                    Required. Name of ssl certificate to add 

  --format     string                  Optional. Format of ssl certificate (default "Pem") 

  --all-in-one-file     string         Optional. Path of file which contain the complete
                                       content of the SSL certificate, including the content
                                       of site certificate, the private key which encrypted
                                       the site certificate, and the CA certificate.  

  --site-certificate-file     string   Optional. Path of user's certificate file, *.crt.
                                       Required if all-in-one-file is omitted 

  --private-key-file     string        Optional. Path of private key file, *.key. Required if
                                       all-in-one-file is omitted 

  --ca-certificate-file     string     Optional. Path of CA certificate file, *.crt 

  --help, -h                           help for add 

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

* [ucloud ulb ssl](developer/cli/cmd/ucloud/ulb/ssl)	 - List and manipulate SSL Certificates for ULB

