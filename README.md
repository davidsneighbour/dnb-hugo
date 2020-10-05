# dnb-hugo

David's Neighbour's repo of Hugo goodness

## Features

- Netlification: a collection of tools that optimize your site on Netlify
- Shortcodes: David's Neighbour's Hugo shortcodes
- Robots: configure the content of your robots.txt with front matter

## Usage

## Installing

Step 1: enable modules in your own repository

```shell script
hugo mod init github.com/username/reponame
```

Step 2: add dnb-hugo to your required modules in config.toml

```
[module]
[[module.imports]]
path = "github.com/daviddsneighbour/dnb-hugo"
```

The next time you run hugo it will download the latest version of the hugo-dnb.

## Updating

To update one module:

```
hugo mod get -u github.com/davidsneighbour/dnb-hugo/packages/netlification
hugo mod get -u github.com/davidsneighbour/dnb-hugo/packages/robots
hugo mod get -u github.com/davidsneighbour/dnb-hugo/packages/shortcodes
```

To update all:

```
hugo mod get -u
```
