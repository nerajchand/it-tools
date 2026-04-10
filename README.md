<picture>
    <source srcset="./.github/logo-dark.png" media="(prefers-color-scheme: light)">
    <source srcset="./.github/logo-white.png" media="(prefers-color-scheme: dark)">
    <img src="./.github/logo-dark.png" alt="logo">
</picture>

<p align="center">
Useful tools for developer and people working in IT. <a href="https://it-tools.tech">Try it!</a>
</p>

## Functionalities and roadmap

Please check the [issues](https://github.com/nerajchand/it-tools/issues) to see if some feature listed to be implemented.

You have an idea of a tool? Submit a [feature request](https://github.com/nerajchand/it-tools/issues/new/choose)!

## Self host

Self host solutions for your homelab

**From github packages:**

```sh
docker run -d --name it-tools --restart unless-stopped -p 8080:8080 ghcr.io/nerajchand/it-tools:latest
```


## Credits

Coded with ❤️ by [Corentin Thomasset](https://corentin.tech?utm_source=it-tools&utm_medium=readme).

## License

This project is under the [GNU GPLv3](LICENSE).
