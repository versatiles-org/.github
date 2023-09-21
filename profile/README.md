# VersaTiles is a stack to generate and serve vector tiles

<img src="https://github.com/versatiles-org/.github/raw/main/profile/stack.svg">

The stack has 5 parts:

- **[generator](https://github.com/versatiles-org/versatiles-generator):** [Tilemaker with Shortbread](https://github.com/versatiles-org/shortbread-tilemaker)
- **[converter](https://github.com/versatiles-org/versatiles-converter):** converts *.mbtiles -> [*.versatiles](https://github.com/versatiles-org/versatiles-spec) using the [VersaTiles tool](https://github.com/versatiles-org/versatiles-rs)
- **[server](https://github.com/versatiles-org/versatiles-documentation/blob/main/basics/versatiles_server.md):** serves tiles
- **[cache](https://github.com/versatiles-org/versatiles-documentation):** CDN/load balancer/nginx/Let's Encrypt,...
- **[frontend](https://github.com/versatiles-org/versatiles-frontend):** includes MapLibre, [styles](https://github.com/versatiles-org/versatiles-styles), [fonts](https://github.com/versatiles-org/versatiles-fonts), [symbols](https://github.com/versatiles-org/versatiles-sprites), ...

The core tool is also called [VersaTiles](https://github.com/versatiles-org/versatiles-rs), is written in Rust, handles tile conversion and includes a full server. We also provide [Docker containers](https://github.com/versatiles-org/versatiles-docker). You can [download tiles covering planet for free](https://download.versatiles.org). More Information is in the [documentation](https://github.com/versatiles-org/versatiles-documentation).

Talk to us on [matrix](https://matrix.to/#/#versatiles:matrix.org).

Visit us on [versatiles.org](https://versatiles.org).
