## Changelog

### [v1.1.4](https://github.com/eBay/fabio/releases/tag/v1.1.4) - Unreleased

 * [Issue #99](https://github.com/eBay/fabio/issues/99): Disable fabio health check in consul
 * [Issue #100](https://github.com/eBay/fabio/issues/100): Keep fabio registered in consul

### [v1.1.3](https://github.com/eBay/fabio/releases/tag/v1.1.3) - 20 May 2016

 * Drop support for Go 1.5
 * [Issue #55](https://github.com/eBay/fabio/issues/55): Expand ${DC} to consul datacenter
 * [Issue #95](https://github.com/eBay/fabio/issues/95): Expand experimental HTTP API
 * [Issue #96](https://github.com/eBay/fabio/issues/96): Allow tags for fabio service registration
 * [Issue #97](https://github.com/eBay/fabio/issues/97): Support PROXY protocol
 * [Issue #98](https://github.com/eBay/fabio/issues/98): Improve forward header
 * [Issue #103](https://github.com/eBay/fabio/issues/103): Trim whitespace around tag
 * [Issue #104](https://github.com/eBay/fabio/issues/104): Keep sort order in UI stable
 * [PR #93](https://github.com/eBay/fabio/pull/93): Add glob path matching

### [v1.1.2](https://github.com/eBay/fabio/releases/tag/v1.1.2) - 27 Apr 2016

 * Upgrade to Go 1.5.4 and Go 1.6.2
 * [PR #74](https://github.com/eBay/fabio/pull/74): Improve forward header handling
 * [Issue #77](https://github.com/eBay/fabio/issues/77): Fix registry.consul.register.addr example in properties
 * [Issue #88](https://github.com/eBay/fabio/issues/88): Use consul node address
 * [Issue #90](https://github.com/eBay/fabio/issues/90): Drop default port from request

### [v1.1.1](https://github.com/eBay/fabio/releases/tag/v1.1.1) - 22 Feb 2016

 * [Issue #57](https://github.com/eBay/fabio/issues/57): Deleted routes hide visible routes
 * [Issue #59](https://github.com/eBay/fabio/issues/59): Latest fabio docker image fails consul check
 * [PR #58](https://github.com/eBay/fabio/pull/58): Fix use of local ip in consul service registration

### [v1.1](https://github.com/eBay/fabio/releases/tag/v1.1) - 18 Feb 2016

 * Drop support for Go 1.4 and build for both Go 1.5.3 and Go 1.6
 * [Issue #12](https://github.com/eBay/fabio/issues/12): Support additional backends
 * [Issue #32](https://github.com/eBay/fabio/issues/32): HTTP2 support with latest Go
 * [Issue #37](https://github.com/eBay/fabio/issues/37): Add support for consul ACL token to demo server
 * [Issue #41](https://github.com/eBay/fabio/issues/41): Cleanup metrics for deleted routes
 * [Issue #43](https://github.com/eBay/fabio/issues/43): Allow configuration via env vars
 * [Issue #47](https://github.com/eBay/fabio/issues/47): Move dependencies to vendor path
 * [Issue #48](https://github.com/eBay/fabio/issues/48): Allow configuration of serviceip used during consul registration
 * [PR #49](https://github.com/eBay/fabio/pull/49): Fix up use of addr in service registration

### [v1.0.9](https://github.com/eBay/fabio/releases/branch/v1.0.9) - 16 Jan 2016

 * [Issue #53](https://github.com/eBay/fabio/issues/53): Make read and write timeout configurable

### [v1.0.8](https://github.com/eBay/fabio/releases/tag/v1.0.8) - 14 Jan 2016

 * Upgrade to Go 1.5.3
 * [Issue #29](https://github.com/eBay/fabio/issues/29): Include service with check ids other than 'service:*'
 * [Issue #30](https://github.com/eBay/fabio/issues/30): Register fabio with local ip address as fallback
 * [Issue #36](https://github.com/eBay/fabio/issues/36): Add support for consul ACL token

### [v1.0.7](https://github.com/eBay/fabio/releases/tag/v1.0.7) - 13 Dec 2015

 * [Issue #22](https://github.com/eBay/fabio/issues/22): fabio route not removed after consul deregister
 * [Issue #23](https://github.com/eBay/fabio/issues/23): routes not removed when passing empty string
 * [Issue #26](https://github.com/eBay/fabio/issues/26): Detect when consul agent is down
 * Allow to override title and color UI

### [v1.0.6](https://github.com/eBay/fabio/releases/tag/v1.0.6) - 01 Dec 2015

 * [Issue #9](https://github.com/eBay/fabio/issues/9): Enabled raw websocket proxy by default
 * [Issue #15](https://github.com/eBay/fabio/issues/15): Traffic shaping now matches on service
 * [Issue #16](https://github.com/eBay/fabio/issues/16): Improved Web UI with better filtering
 * [Issue #18](https://github.com/eBay/fabio/issues/18): Manage manual overrides via ui

### [v1.0.5](https://github.com/eBay/fabio/releases/tag/v1.0.5) - 11 Nov 2015

 * [Issue #9](https://github.com/eBay/fabio/issues/9): Add experimental support for web sockets
 * [Issue #10](https://github.com/eBay/fabio/issues/10): Add support for `Forwarded` and `X-Forwarded-For` header
 * Add `proxy.localip` to set proxy ip address for headers

### [v1.0.4](https://github.com/eBay/fabio/releases/tag/v1.0.4) - 03 Nov 2015

 * [Issue #8](https://github.com/eBay/fabio/issues/8): Add support for SSL client certificate authentication

### [v1.0.3](https://github.com/eBay/fabio/releases/tag/v1.0.3) - 25 Oct 2015

 * Add Docker support and official Docker image `magiconair/fabio`

### [v1.0.2](https://github.com/eBay/fabio/releases/tag/v1.0.2) - 23 Oct 2015

 * [PR #3](https://github.com/eBay/fabio/pull/3): Honor consul.url and consul.addr from config file (@jeinwag)

### [v1.0.1](https://github.com/eBay/fabio/releases/tag/v1.0.1) - 21 Oct 2015

 * Honor maintenance mode for both services and nodes

### [v1.0.0](https://github.com/eBay/fabio/releases/tag/v1.0.0) - 16 Oct 2015

 * Initial open-source release

