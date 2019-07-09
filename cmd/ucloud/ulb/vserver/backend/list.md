{{indexmenu_n>1}}

# list

\#\# ucloud ulb vserver backend list

List ULB VServer backend nodes

\#\#\# Synopsis

List ULB VServer backend nodes

\`\`\` ucloud ulb vserver backend list \[flags\] \`\`\`

\#\#\# Options

\`\`\`

``` 
--ulb-id     string       Required. Resource ID of ULB which the backend nodes belong to 
```

``` 
--vserver-id     string   Required. Resource ID of VServer which the backend nodes belong to 
```

``` 
--region     string       Optional. Override default region, see 'ucloud region' (default
                          "cn-bj2") 
```

``` 
--project-id     string   Optional. Override default project-id, see 'ucloud project list'
                          (default "org-ryrmms") 
```

``` 
--help, -h                help for list 
```

\`\`\`

\#\#\# Options inherited from parent commands

\`\`\`

``` 
--debug, -d   Running in debug mode 
```

``` 
--json, -j    Print result in JSON format whenever possible 
```

\`\`\`

\#\#\# SEE ALSO

\* \[ucloud ulb vserver
backend\](software/cli/cmd/ucloud/ulb/vserver/backend) - List and
manipulate VServer backend nodes
