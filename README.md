# multi-flow-listener
Artifacts for multi-flow listeners

Not officially supported.

```
IntegrationServer -w ~/tmp/multi-flow-work-dir --user-multi-flow-listener "https://raw.githubusercontent.com/tdolby-at-uk-ibm-com/multi-flow-listener/main"
```

To run the tea BAR file, add the credentials before starting the server:
```
mqsisetdbparms -w ~/tmp/multi-flow-work-dir -n jdbc::tea -u <db2 userid> -p <db2 password>
```
