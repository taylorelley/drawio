# draw.io Community Edition (draw.io-ce)

draw.io Community Edition (draw.io-ce) is an open-source diagramming and whiteboarding application. This community-driven fork is based on the original draw.io project by JGraph Ltd, with a focus on open collaboration and transparency.

**Notable in this fork:** Reintroduced Microsoft Visio (.vsdx) export support.

## Features

- Flexible diagramming and whiteboarding experience
- Multiple themes and templates
- Export options including SVG, PNG, PDF, and VSDX (in this fork)
- Runs in a modern browser with no required backend

## Getting started

### Run locally

1. Fork or clone this repository.
2. Serve `src/main/webapp/index.html` with any static file server.

### Run with hosting or packaging

- Publish the `master` branch to GitHub Pages for a quick static deployment.
- Use the recommended Docker project at https://github.com/jgraph/docker-drawio.
- Download draw.io Desktop from https://get.diagrams.net.

The packaged `.war` of the client and servlets is built when the project is tagged and available on the releases page: https://github.com/taylorelley/drawio-ce/releases.

## Supported browsers

draw.io supports Chrome 123+, Firefox 120+, Safari 17.5+, Opera 109+, WebView Android 137+, Safari iOS 18.5+, and Edge 123+.

## Contributing

We welcome pull requests and contributions from anyone, including the use of Gen AI tools, provided changes are clearly described and effectively tested.

Please include:

- A clear summary of changes
- Tests or validation steps you ran
- Any relevant screenshots or UI notes

If you are unsure where to start, open an issue and describe what you want to improve.

## License

draw.io-ce is open source and licensed under the Apache 2.0 license.

This fork is based on the original draw.io project by JGraph Ltd (https://github.com/jgraph/drawio) and includes Apache v2 licensing attribution to the upstream authors where applicable.

The JGraph provided icons and diagram templates are licensed under the [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). Additional terms may also apply where the icons are originally defined by a third-party copyright holder. We have checked in all cases that the original license allows use in this project. Also see the terms for using the draw.io logo below.

Additional minified JavaScript files and Java libraries are used in this project. All of the licenses are deemed compatible with the Apache 2.0, nothing is GPL or AGPL, due diligence is performed on all third-party code.

We make no copyright claim on the content you create with this software, regardless of the copyright of individual icons used in such content.

## Upstream project notes

The upstream project runs a production-grade deployment of the diagramming interface at https://app.diagrams.net.

The upstream project notes that it is written by humans only and does not accept PRs. Those restrictions do not apply to draw.io-ce.

The upstream project has its own licensing and contribution restrictions that do not apply to draw.io-ce.

## Scope of the project

draw.io is a diagramming or whiteboarding application, depending on which theme is selected. It is not an SVG editing app; the SVG export is designed only for embedding in web pages, not for further editing in other tools.

draw.io-ce is not intended as a framework for building other products from; for this try either [Tldraw](https://github.com/tldraw/tldraw) or [Excalidraw](https://github.com/excalidraw/excalidraw).

Note, in particular, we don't have support for collaborative editing in this project. If this is important, one of the projects above is likely a better choice.

If you are using a draw.io project/product and have issues or questions about the editor itself, the issue tracker and discussion in this GitHub project are likely a good place to look.

## Logo and trademark usage

draw.io is a registered EU trademark, #018062448.

Do not use the draw.io name or any draw.io logo in a way that suggests you are JGraph, your offering or project is by JGraph, or that JGraph is endorsing you or your offering or project.

Do not use any draw.io logo as the icon or logo for your business/organization, offering, project, domain name, social media account, or website.

Do not modify the permitted draw.io logos, including changing the color, dimensions, or combining with other words or design elements.

Do not use JGraph trademarks or logos without JGraph’s prior written permission.
