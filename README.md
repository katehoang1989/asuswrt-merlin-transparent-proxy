# Use Asuswrt Merlin as a transparent proxy

## Intro

This project is for config you asus router (merlin based) to serve as a transparent forward proxy.

## Prerequisites

- A VPS which can server as a shadowsocks server. (Or third party service)
- A router which support opkg package manager. (we use Merlin, I think OpenWRT can satisfied too after some hack)
- A local ssh client which can login to router.

## Feature

[ss+chinadns](https://github.com/zw963/asuswrt-merlin-transparent-proxy/blob/v0.3.6/ss%2Bchinadns)

[ss+chinadns+dnscrypt](https://github.com/zw963/asuswrt-merlin-transparent-proxy/blob/v0.3.6/ss%2Bchinadns%2Bdnscrypt)

[ss+dnsmasq+dnscrypt](https://github.com/zw963/asuswrt-merlin-transparent-proxy/blob/v0.3.6/ss%2Bdnsmasq%2Bdnscrypt)

[ss+udprelay](https://github.com/zw963/asuswrt-merlin-transparent-proxy/blob/v0.3.6/ss%2Bdnsmasq%2Budprelay)

For details, please see [Wiki](https://github.com/zw963/asuswrt-merlin-transparent-proxy/wiki) link.

## TODO

Integrate AD filtering into install script (see https://diversion.ch)

## Contributing

  * [Bug reports](https://github.com/zw963/asuswrt-merlin-transparent-proxy/issues)
  * Patches:
    * Fork on Github.
    * Create your feature branch: `git checkout -b my-new-feature`.
    * Commit your changes: `git commit -am 'Add some feature'`.
    * Push to the branch: `git push origin my-new-feature`.
    * Send a pull request :D.
