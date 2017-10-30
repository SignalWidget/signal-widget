
# Signal Widget Client Customization Library for Web Developers

[Signal Widget](https://www.signal-widget.com) makes it easy to publish announcements
on your website. 

[Signal Widget](https://www.signal-widget.com/use-cases) already ships with a 
few classical themes like Bootstrap, Material and Foundation.

Custom CSS can be added right in the Editor. 

**This is for people, who want to build a custom theme** and harness
the power of scss, webpack and other automated processing.

This boilerplate helps you to get started with your custom theme.

## Installation

```shell
npm install signal-widget
```

## (WIP) Development

**Integrate it into your current build process for now**

Checkout the already included themes and start to customize them.
If your Theme is based on Bootstrap, you can start easily with the 
`bootstrap/signal-widget.scss` and adjust the variables and add custom 
css rules.

```shell
npm run dev
```
creates a local server with hot reload and file watching (using webpack)

## (WIP) Build

This packs and compresses the scss and icons and creates a nice css, which 
can get inserted right into the custom css field in the editor.
```shell
npm run build
```

## License

[MIT License Copyright 2017 Tim Kirbach](license.md)

