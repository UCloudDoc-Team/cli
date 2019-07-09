{{indexmenu_n>3}}

# delete

\#\# ucloud mysql db delete

Delete MySQL instances by udb-id

\#\#\# Synopsis

Delete MySQL instances by udb-id

\`\`\` ucloud mysql db delete \[flags\] \`\`\`

\#\#\# Options

\`\`\`

``` 
--udb-id     strings      Required. Resource ID of UDB instances to delete 
```

``` 
--region     string       Optional. Override default region, see 'ucloud region' (default
                          "cn-bj2") 
```

``` 
--zone     string         Optional. Override default availability zone, see 'ucloud region'
                          (default "cn-bj2-02") 
```

``` 
--project-id     string   Optional. Override default project-id, see 'ucloud project list'
                          (default "org-ryrmms") 
```

``` 
--yes, -y                 Optional. Do not prompt for confirmation. 
```

``` 
--help, -h                help for delete 
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

\* \[ucloud mysql db\](software/cli/cmd/ucloud/mysql/db) - Manange MySQL
instances
