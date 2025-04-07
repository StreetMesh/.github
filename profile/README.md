# StreetMesh

[![CC BY-NC-SA 4.0][cc-by-nc-sa-shield]][cc-by-nc-sa]

*StreetMesh* is an open source framework for spatially organizing the web, building upon open standards and existing protocols. This repository documents this framework and anchors the effort to *The Dream*.

## The Dream

We dream of a virtual world where people can live active, productive lives full of wonder and community. This *metaverse* translates the information systems we have today into richly visual environments: websites of all kinds can make their homes here.

Like the real world and unlike the web, our virtual world is *spatialized*: it is a vast, interconnected place that can be explored, in which areas of interest have permanent locations, businesses can have stores, and people can have domiciles.

Life happens here. People make new connections in our virtual world. They play games, start movements and businesses, and even fall in love. People study the real world using sophisticated virtual tools for visualization and analysis. People earn degrees here.

Commerce happens here. Stores in our virtual world pull their inventory directly from e-commerce websites. We can purchase virtual goods here and store them in our domiciles, and we can order material goods to be shipped to our homes in the real world.

Events happen here. People gather in our virtual world to celebrate all matters of social and cultural importance. Community is built here. Real-life events are streamed to our virtual world, allowing their organizers to reach new and far-flung audiences.

This is not a product but a platform. It belongs to no one and everyone. Built on the web’s existing foundation, it invites creators, thinkers, builders, and dreamers to shape it freely. 

Our virtual world is not just the next version of the Internet—it's a spatial web of information, people, and life—the *StreetMesh*.

---

*The Dream continues in the [Experiences](https://github.com/StreetMesh/Experience) project.*

## License

This work—that is, the content of this repository—is licensed under a
[Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License][cc-by-nc-sa].

[cc-by-nc-sa]: http://creativecommons.org/licenses/by-nc-sa/4.0/
[cc-by-nc-sa-image]: https://licensebuttons.net/l/by-nc-sa/4.0/88x31.png
[cc-by-nc-sa-shield]: https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg

Other projects linked here are governed by their licenses.

## The Name

The name StreetMesh is inspired by Neal Stephenson's book *Snow Crash*:

> The Street in *Snow Crash* is the backbone of the Metaverse—a single, grand boulevard that stretches for thousands of kilometers in virtual space. It’s a shared, persistent environment where avatars walk, talk, trade, and interact. Created and maintained by the Global Multimedia Protocol Group, The Street is lined with buildings, parks, shops, and clubs built by users, corporations, and developers, each parceling out space like digital real estate. Everything in the Metaverse revolves around The Street—it’s the main artery of virtual life, a 3D manifestation of the internet where social status is coded into the fidelity of your avatar and the size of your domain. Whether you’re a hacker, a mogul, or a wanderer, The Street is where you show up, plug in, and take part in the digital sprawl.

## Core Values

The design and development of StreetMesh are guided by these values:

### Humanity

[Humanity](https://en.wikipedia.org/wiki/Humanity_(virtue)) is a virtue linked with altruistic ethics derived from the human condition. It signifies human love and compassion towards each other. Not all human endeavors embody humanity: as a species, we are as likely to be humane as we are to be inhumane. Thus, humanity must be intentional—it must be factored into the design of things, lest those things be devoid. 

### Creativity

### Transparency

### Interoperability

### Decentralization

### Modularity

### Accessibility

## Architecture

This section is not exhaustive. For a deep dive, see *Projects* below.

StreetMesh is a decentralized solution for spatializing the web, which itself is a decentralized system.

To access the traditional web, users use *Web Browsers* (like [Chrome](https://www.google.com/chrome/) and [Safari](https://www.apple.com/safari/)) to connect to *Web Servers* (like [nginx](https://nginx.org/)), download, and render text and binary data into mostly 2D and some 3D user interfaces.

To access the spatialized web, users use *StreetMesh Browsers* to connect to *StreetMesh Servers*, download, and render text and binary data into mostly 3D and some 2D user interfaces.

### StreetMesh Servers

A *StreetMesh Server* is software that runs on top of a standards-compliant web server. StreetMesh Servers perform a range of functionalities, including:

* Hosting User Avatars and their Public and Private Data
* Hosting Assets and 3D Tile Data, giving form to the virtual world
* Authenticating Identities and Authorizing Communication between Users and Servers
* Registering and Advertising Trustworthy StreetMesh Servers and Sites
* Facilitating Transactions Between People and Companies
* Coordinating Peer-To-Peer Communication Channels
* Networking Multiplayer Game State

### StreetMesh Browsers

Any software system can be taught to communicate with a *StreetMesh Server*. In this broad sense, if a software system can communicate with a *StreetMesh Server*, then it can act as a *StreetMesh Browser*. 

Streetmesh Servers rely on standard Internet protocols like HTTP, TCP, and UDP for communication with clients and other servers. Thus, any standards-compliant Web browser can act as a StreetMesh Browser. The quality and fidelity of the content served are limited or enhanced by the browser used to consume it.

## Projects

These current and future projects give life to the ideas in the *StreetMesh* framework.

* [Experience](https://github.com/StreetMesh/Experience) - A collection of illustrated essays that describe life in the virtual world
* [Experiments](https://github.com/StreetMesh/Experiments) - Small prototypes of StreetMesh components running in a single [Laravel](https://laravel.com/) container
* [Protocol](https://github.com/StreetMesh/Protocol) - The rules guiding communication between StreetMesh Servers and Browsers
* [Avatars](https://github.com/StreetMesh/Avatars) - Avatars are People and Programs, Places, and Things that inhabit StreetMesh servers
* [Iconography](https://github.com/StreetMesh/Icons) - Standard iconography for an accessible virtual world, using [Font Awesome](https://fontawesome.com/)
* [StreetTiles](https://github.com/StreetMesh/StreetTiles) - An application of [Cesium 3D Tiles](https://github.com/CesiumGS/3d-tiles) for compositing StreetMesh environments
* [Browser](https://github.com/StreetMesh/Browser) - A reference implementation of an embedded StreetMesh Browser, with support for XR, built with [react-three-fiber]([https://github.com/pmndrs/react-three-fiber])
* [Server](https://github.com/StreetMesh/Server) - A reference implementation of a StreetMesh Server, built with [Laravel](https://laravel.com/)
* [Hub](https://github.com/StreetMesh/Hub) - A reference implementation of a StreetMesh Authoritative Multiplayer Host, built with [Colyseus](https://colyseus.io)
* [MeshObject](https://github.com/StreetMesh/MeshObject) - [Microdata](https://schema.org/) format HTML pages can use to serve 3D Models and other data to StreetMesh Browsers
* [StreetMaps](https://github.com/StreetMesh/StreetMaps) - An extension of [Sitemap](https://www.sitemaps.org/), for indexing web content for crawling by StreetMesh Servers
* [StreetPress](https://github.com/StreetMesh/StreetPress) - A plugin that adapts [WordPress](https://wordpress.org/)/[WooCommerce](https://woocommerce.com/) sites into StreetMesh Sites
* [Portal](https://github.com/StreetMesh/Portal) - Connecting StreetMesh Servers to real-world locations using 360 and 180 video streaming
* [Window](https://github.com/StreetMesh/Window) - Connecting StreetMesh Servers to real-world locations using 2D video streaming
* [Registry](https://github.com/StreetMesh/Registry) - A directory of safe and interesting StreetMesh compatible servers

## Contributing

### Contributors

* [@collegeman](https://github.com/collegeman) (Founding Contributor)




