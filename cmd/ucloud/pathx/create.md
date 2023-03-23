## ucloud pathx create

Create the pathx resource and port

### Synopsis

Create global unified access acceleration configuration item

```
ucloud pathx create [flags]
```

### Examples

```
ucloud pathx create --bandwidth 10 --area-code DXB--charge-type Month --quantity 4 --accel Global --origin-ip 110.111.111.111--protocol TCP --port 30654 --origin-port 30564
```

### Options

```
  --project-id     string      Optional. Override default project-id for this command
                               invocation, see 'ucloud project list' 

  --region     string          Optional. Override default region for this command invocation,
                               see 'ucloud region' 

  --zone     string            Optional. Override default availability zone for this command
                               invocation, see 'ucloud region' 

  --bandwidth     string       Required. Shared bandwidth of the resource 

  --area-code     string       Optional. When it is empty,the nearest zone will be selected
                               based on the origin-domain and origin-ip. Acceptable
                               values:'BKK'(曼谷),'DXB'(迪拜),'FRA'(法兰克福),'SGN'(胡志明市),'HKG'(香港),'CGK'(雅加达),'LOS'(拉各斯),'LHR'(伦敦),'LAX'(洛杉矶),'MNL'(马尼拉),'BOM'(孟买),'MSP'(圣保罗),'ICN'(首尔),'PVG'(上海),'SIN'(新加坡),'NRT'(东京),'IAD'(华盛顿),'TPE'(台北) 

  --charge-type     string     Optional. Payment method,its value is not case
                               sensitive,acceptable values:'Year',pay yearly;'Month',pay
                               monthly;'Hour', pay hourly 

  --quantity     int           Optional. The duration of the pathx resource, the value cannot
                               be less than or equal to 0. N years/months (default 1) 

  --accel     string           Optional. The default value is 'Global'(全球). Other
                               acceptable
                               values:'AP'(亚太);'EU'(欧洲);'ME'(中东);'OA'(大洋洲);'AF'(非洲);'NA'(北美洲);'SA'(南美洲) 

  --origin-ip     string       Optional. But when the origin-domain is empty,it cannot be
                               empty. If multiple values exist,please split by ','. For
                               example '0.0.0.0,110.110.100.100' 

  --origin-domain     string   Optional. But when the origin-ip is empty,it cannot be empty 

  --port     strings           Optional. Disable 65123 port,the port can be multiple,please
                               split by ',' for example 80,3000-3010. The number of port must
                               be consistent with the number of origin-port,and the number
                               cannot greater than or equals to 10 

  --origin-port     strings    Optional. The origin-port can be multiple,please split by ','
                               for example 80,3000-3010.The number of origin-port must be
                               consistent with the number of port 

  --protocol     string        Its values can be TCP and UDP, but currently only supports TCP
                               (default "TCP") 

  --help, -h                   help for create 

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

* [ucloud pathx](cli/cmd/ucloud/pathx)	 - Manipulate uga and upath instances

