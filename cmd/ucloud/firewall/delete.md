{{indexmenu_n>7}}

# delete

\#\# ucloud firewall delete

Delete firewall by resource ids or names

\#\#\# Synopsis

Delete firewall by resource ids or names

\`\`\` ucloud firewall delete \[flags\] \`\`\`

\#\#\# Examples

\`\`\` ucloud firewall delete --fw-id firewall-xxx \`\`\`

\#\#\# Options

\`\`\`

``` 
--fw-id     strings       Required. Resource IDs of firewall to delete 
```

``` 
--region     string       Optional. Region, see 'ucloud region' (default "cn-bj2") 
```

``` 
--project-id     string   Optional. Project-id, see 'ucloud project list' (default "org-ryrmms") 
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

\* \[ucloud firewall\](software/cli/cmd/ucloud/firewall) - List and
manipulate extranet firewall
