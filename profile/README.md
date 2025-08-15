# VersaTiles is a free stack for generating and serving map tiles.

<img src="https://github.com/versatiles-org/.github/raw/main/profile/stack.svg">

The stack has 4 parts:

- **[Generator](https://github.com/versatiles-org/versatiles-generator):** [Tilemaker with Shortbread](https://github.com/versatiles-org/shortbread-tilemaker)
- **[Server](https://docs.versatiles.org/basics/versatiles_server):** A high-performance, Rust-based server that efficiently serves tiles over HTTP
- **[Network](https://docs.versatiles.org/compendium/specification_reference_model#layer-network):** CDN/load balancer/nginx/Let's Encrypt, ...
- **[Frontend]([https://github.com/versatiles-org/versatiles-frontend](https://docs.versatiles.org/basics/frontend.html)):** contains MapLibre, [styles, symbols](https://github.com/versatiles-org/versatiles-style), [fonts](https://github.com/versatiles-org/versatiles-fonts), ...

The core tool is also called [VersaTiles](https://github.com/versatiles-org/versatiles-rs), is written in Rust, handles tile conversion and includes a full server. We also provide [Docker containers](https://github.com/versatiles-org/versatiles-docker). You can [download all tiles for free](https://download.versatiles.org). More information can be found in the [documentation](https://docs.versatiles.org/)

If you want to help, check issues tagged [`help wanted`](https://github.com/search?q=org%3Aversatiles-org+label%3A%22help+wanted%22+state%3Aopen&type=issues).

Follow us on [Mastodon](https://mastodon.social/@VersaTiles) or [Bluesky](https://bsky.app/profile/versatiles.bsky.social).

Visit us on [versatiles.org](https://versatiles.org).
