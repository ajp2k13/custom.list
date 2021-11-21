# /etc/pihole/custom.list
A way to enforce Safe Search for Google, Bing, DuckDuckGo, YouTube, and Pixabay w/o editing dnsmasq config files.


## Usage
Add the `custom.list` file in this repo to `/etc/pihole/` as `custom.list` by running the follow line.

`sudo wget https://raw.githubusercontent.com/mwoolweaver/custom.list/master/custom.list -O /etc/pihole/custom.list`

then restart the pihole-FTL service for the changes to be active.

`sudo service pihole-FTL restart`

you might also have to flush the dns cache on the devices using Pi-hole.
