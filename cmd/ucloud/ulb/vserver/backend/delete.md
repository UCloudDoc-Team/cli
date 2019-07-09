{{indexmenu_n>4}}

# delete

\#\# ucloud ulb vserver backend delete

Delete ULB VServer backend nodes

\#\#\# Synopsis

Delete ULB VServer backend nodes

\`\`\` ucloud ulb vserver backend delete \[flags\] \`\`\`

\#\#\# Options

\`\`\`

``` 
--ulb-id     string        Required. Resource ID of ULB which the backend nodes belong to 
```

``` 
--backend-id     strings   Required. BackendID of backend nodes to update 
```

``` 
--region     string        Optional. Override default region, see 'ucloud region' (default
                           "cn-bj2") 
```

``` 
--project-id     string    Optional. Override default project-id, see 'ucloud project list'
                           (default "org-ryrmms") 
```

``` 
--help, -h                 help for delete 
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
