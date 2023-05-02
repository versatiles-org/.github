# VersaTiles is a stack to generate and serve vector tiles

<img src="https://github.com/versatiles-org/.github/raw/main/profile/stack.svg">

The stack has 5 parts:

- **generator** [tilemaker with shortbread](https://github.com/versatiles-org/versatiles-generator) 
- **converter** [*.mbtiles -> *.versatiles](https://github.com/versatiles-org/versatiles-converter)
- **server** [serves versatiles](https://github.com/versatiles-org/versatiles-server)
- **cache** CDN/nginx/...
- **frontend** [MapLibre, styles, fonts, symbols, ...](https://github.com/versatiles-org/versatiles-frontend)

The core tool is called "[versatiles](https://github.com/versatiles-org/versatiles-rs)", is written in Rust, handles tile conversion and includes a full server.

You can find the [how-to's in the documentation](https://github.com/versatiles-org/versatiles-documentation)