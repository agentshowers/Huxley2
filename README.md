# Huxley 2 Community Edition

A cross-platform JSON proxy for the GB railway Live Departure Boards SOAP API

![Huxley](Huxley2/wwwroot/img/huxley.png)

This project is treeware! If you found it useful then please [plant a tree for me](https://offset.earth/unitsetsoftware).

[![Buy me a tree!](Huxley2/wwwroot/img/buy-me-a-tree.svg)](https://offset.earth/unitsetsoftware)

## About

Huxley 2 is a CORS enabled cross-platform JSON ReST proxy for the GB NRE LDB WCF SOAP XML API (called Darwin). It supports both the Public Version (PV) and the Staff Version (SV). It's built with ASP.NET Core LTS, C# 8.0 and lots of abbreviations!

The primary purpose of Huxley 2 is to allow easy use of the LDB API from browser-based client-side PWAs made with JavaScript or TypeScript. Additionally, it opens up the Windows enterprise API to agile developers on macOS and Linux. 

## Get Started

Check out [the live demo server](https://huxley2.azurewebsites.net/) for API documentation and to give it a try.

The demo server comes with zero guarantees of uptime.
It can (and regularly does) go down or break.

## Get Your Own

There are detailed instructions on how to host your own instance on Azure in [this blog post](https://unop.uk/huxley-2-release/).

### Running with Docker

1. Ensure you have Docker and Docker Compose installed
2. Create an `.env` file in the `Huxley2` directory with the access tokens. You can delete the ones you're not using. Example:
```
ACCESS_TOKEN=abcde12345
STAFF_ACCESS_TOKEN=abcde12345
CLIENT_ACCESS_TOKEN=abcde12345
```
3. Run `docker-compose up`
4. The app should be available at `localhost:8081`

## License

Licensed under the [EUPL-1.2-or-later](https://joinup.ec.europa.eu/collection/eupl/introduction-eupl-licence).

The EUPL covers distribution through a network or SaaS (like a compatible and interoperable AGPL).
