# x

A survival Minecraft server managed by [mc](https://github.com/afrigon/mc).

The server is fully described by `mc.toml`: Minecraft version, mod loader,
mods, world settings, and backup schedule. `mc.lock` pins the exact mod
versions.

## Running

[mise](https://mise.jdx.dev) installs mc and runs the server:

```sh
mise install
mise run server
```

This loads the Discord webhook from 1Password and starts the server with
`mc run`. To run without the webhook:

```sh
mc run
```
