## ghastly device

sub-commands for manipulating and interacting with devices

### Synopsis

sub-commands for manipulating and interacting with devices

### Options

```
  -h, --help   help for device
```

### Options inherited from parent commands

```
      --loglevel string   log level; one of TRACE, DEBUG, INFO, WARN, ERROR, FATAL, PANIC (default "INFO")
  -o, --output text       output format for commands; options are text or `json` (default "text")
      --server string     the URL used to access homeassistant. defaults to value of HASS_SERVER environment variable (default "http://nuc.lan:8123")
      --token string      the bearer token used to authenticate to homeassistant. defaults to value of HASS_TOKEN environment variable (default "eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJpc3MiOiJjZGZlZDAwNDE1NmM0NTM2YTI4MDRiMmRiMjUzN2JmMCIsImlhdCI6MTU0OTc2Mzc3MywiZXhwIjoxODY1MTIzNzczfQ.wHtNVzQoEb1hY5m86QaEKOIp5pApyO0HZBJBDjfCJZc")
```

### SEE ALSO

* [ghastly](ghastly.md)	 - ghastly is a tool for interacting with homeassistant
* [ghastly device get](ghastly_device_get.md)	 - retrieve a specific device with the given ID
* [ghastly device list](ghastly_device_list.md)	 - retrieve a list of all known devices
* [ghastly device search](ghastly_device_search.md)	 - search for devices, using a simplified lucene syntax: `field:value {AND,OR} otherfield:othervalue`

###### Auto generated by spf13/cobra on 17-May-2020