#New Relic Haproxy Plugin for Upstart

This upstart script is designed to turn the Railsware New Relic Haproxy plugin into a daemon. 

## What you need to do
Simply clone the .conf file and put into this directory "/etc/init" (not init.d)

Make sure root is the owner of the file and that the .conf file has 0644 permissions

Finally, run "start newrelic_haproxy_agent_upstart"

You should notice New Relic beginning to collect metrics. 

