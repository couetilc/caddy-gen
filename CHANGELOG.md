# Changelog

## Version 1.0.0

- feat: added labels for adding directives to host and proxy blocks. Those are
  `virtual.host.directives`, `virtual.host.import`, `virtual.proxy.matcher`,
  `virtual.proxy.lb_policy`, `virtual.proxy.directives`, `virtual.proxy.import`
- feat: added option to supply a custom template and snippet file to `docker-gen`
  using environment variables CADDY_TEMPLATE and CADDY_SNIPPET.
- chore: Update docker-gen to 0.7.5
- chore: Update Caddy to 2.3.0

## Version 0.3.0

- Updates `alpine` version to `3.11`
- Adds `http` basic auth
- Adds `docker-image-size-limit`


## Version 0.2.0

- Updates `alpine` version to `3.10`
- Updates `Caddy` version to `0.10.12`
- Adds `"virtual.websockets"` configuration to work with websockets
- Adds `docker-image-size-limit`
- Minifies image as possible


## Version 0.1.0

- Updates `alpine` version to `3.7`
- Updates `Caddy` version
- Updates `DockerGen` version
- Adds new labels, including: `vendor` and `version`


## Version 0.0.2

- Add optional domain alias, so alias will redirect to the main host


## Version 0.0.1

- Initial release
