# logstash-pfsense

Collections of files we use to process log send by pfSense firewall using LogStash.
Based on https://github.com/pfelk/pfelk

## Usage
- Install logstash as you would normally do
- Put `patterns` in `/etc/logstash`
- Put `conf.d` also in `/etc/logstash`
- Edit configuration according to your need (we remove a lot of unwanted fields)

## Related project
https://github.com/alkivi-sas/logstash-nftables-updater
