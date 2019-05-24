# duckdns
script to update duckdns.org records

# Install
Create a configuration file, by default at:
```
/etc/duckdns.conf
```
(See sample configuration file.)

Make the script executable and possibly add it to cron, for example:
```
*/3 * * * * /path/to/duckdns >/dev/null 2>&1
```
