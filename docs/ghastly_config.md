## ghastly config

sub-commands for manipulating and interacting with config entries

### Synopsis

sub-commands for manipulating and interacting with config entries

### Options

```
  -h, --help   help for config
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
* [ghastly config get-config](ghastly_config_get-config.md)	 - retrieve the top-level system config
* [ghastly config get-flow](ghastly_config_get-flow.md)	 - retrieve the config flow associated with the given ID
* [ghastly config get-options-flow](ghastly_config_get-options-flow.md)	 - retrieve the current state of the indicated options flow
* [ghastly config list-entries](ghastly_config_list-entries.md)	 - retrieve a list of all known config entries
* [ghastly config list-flow-handlers](ghastly_config_list-flow-handlers.md)	 - returns a list of flow handlers, whatever those are
* [ghastly config list-flows](ghastly_config_list-flows.md)	 - list in-progress but not started config flows
* [ghastly config set-flow](ghastly_config_set-flow.md)	 - set the given key-value pairs on the flow with the given ID
* [ghastly config start-options-flow](ghastly_config_start-options-flow.md)	 - start a config flow with with the given handler ID as the handler

###### Auto generated by spf13/cobra on 21-Aug-2020
