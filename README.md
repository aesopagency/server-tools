# Server Tools

### Swap Space

Adds 4x the amount of memory as swap space

```bash
wget -O - https://raw.githubusercontent.com/aesopagency/server-tools/master/swap | bash
```

### New Relic

Sets up New Relic server monitoring agent. Must provide license key as first argument

```bash
wget -O - https://raw.githubusercontent.com/aesopagency/server-tools/master/newrelic | bash -s {{key}}
```
