# VersaTiles

**A free, open-source stack for generating and self-hosting map tiles** — build your own OpenStreetMap-based maps without per-view fees or vendor lock-in.

![The VersaTiles stack: from raw data to the user's browser](stack.svg)

## The stack has 4 parts

- **[Data](https://docs.versatiles.org/guides/generate_tiles_from_osm):** [Planetiler with Shortbread](https://github.com/versatiles-org/versatiles-docker/tree/main/versatiles-planetiler)
- **[Server](https://docs.versatiles.org/basics/versatiles_server):** A high-performance, Rust-based server that efficiently serves tiles over HTTP
- **[Network](https://docs.versatiles.org/compendium/specification_reference_model#layer-network):** CDN/load balancer/nginx/Let's Encrypt, ...
- **[Frontend](https://docs.versatiles.org/basics/frontend.html):** contains MapLibre, [styles, symbols](https://github.com/versatiles-org/versatiles-style), [fonts](https://github.com/versatiles-org/versatiles-fonts), ...

## Get started

The core tool is also called [VersaTiles](https://github.com/versatiles-org/versatiles-rs). It's written in Rust, handles tile conversion, and includes a full server. We also provide [Docker containers](https://github.com/versatiles-org/versatiles-docker).

You can [download all tiles for free](https://download.versatiles.org), and everything is explained in the [documentation](https://docs.versatiles.org/).

## Support & community

If your team relies on it, please support us on [GitHub](https://github.com/sponsors/versatiles-org) or [OpenCollective](https://opencollective.com/versatiles).

Follow us on [Mastodon](https://mastodon.social/@VersaTiles) or [Bluesky](https://bsky.app/profile/versatiles.bsky.social), and visit us on [versatiles.org](https://versatiles.org).
