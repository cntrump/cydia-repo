# Lvv's Repo

Make some funny. [View on GitHub](https://github.com/cntrump/cydia-repo)

Add cydia source: `https://cydia.lvv.me`

## Clash

Home: [https://github.com/Dreamacro/clash](https://github.com/Dreamacro/clash)

A rule-based tunnel in Go.

Depends: `iOS Firmware >= 10.0`

dashboard: `http://127.0.0.1:9090/ui`

config: `/usr/etc/clash/config.yaml`

restart: `launchctl kickstart -k system/com.github.Dreamacro.clash`

## Trojan-Go

Home: [https://github.com/p4gefau1t/trojan-go](https://github.com/p4gefau1t/trojan-go)

A Trojan proxy written in Go.

Depends: `iOS Firmware >= 10.0`

config: `/usr/etc/trojan-go/config.json`

log: `/var/log/trojan-go`

restart: `launchctl kickstart -k system/com.github.p4gefau1t.trojan-go`

## Caddy

Home: [https://github.com/caddyserver/caddy](https://github.com/caddyserver/caddy)

Caddy 2 is a powerful, enterprise-ready, open source web server with automatic HTTPS written in Go.

Depends: `iOS Firmware >= 10.0`

config: `/usr/etc/caddy/Caddyfile`

root: `/usr/etc/caddy/www`

log: `/var/log/caddy`

restart: `launchctl kickstart -k system/com.github.caddyserver.caddy`