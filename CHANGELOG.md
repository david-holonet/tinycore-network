# Changelog

## 1.4.0 (2016-10-03)

  * Change script output colour
  * Manually manage /etc/hosts instead of calling sethostname

## 1.3.0 (2016-03-24)

  * Add original udhcpc.script from BusyBox
  * Add LICENSE-GPL for BusyBox's udhcpc scripts

## 1.2.1 (2016-03-23)

  * Log static/dhcp output to `/var/log/udhcpc.log`
  * Add some coloured output

## 1.2.0 (2016-03-03)

  * Add IPv6 support through custom DHCP events script: 'udhcpc.script'
  * Wait for devices & network interface to be UP
  * Ensure udhcpc is restarted when hostname changes
  * Ensure interfaces are reset when switching from dhcp to static
  * Update License year

## 1.1.0 (2015-09-17)

  * Change the hostname if the value is set

## 1.0.0 (2015-09-16)

  * Initial release
