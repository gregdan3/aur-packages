# AUR Packages

A monorepo for all AUR package I maintain. [Inspired by hapakaien.](https://github.com/hapakaien/aur-packages/)

## Motivation

I didn't want to dedicate a VPS to scheduling upgrades, and I wanted to maintain these packages because I've used them and benefited from them before. Some packaged by me, some picked up from unmaintained tools.

## Where'd the other sections go?

See [hapakaien's README](https://github.com/hapakaien/aur-packages/blob/main/README.md).

## Packages

### doppler-cli-bin

[![GitHub Workflow Status](https://img.shields.io/github/actions/workflow/status/gregdan3/aur-packages/doppler-cli-bin.yml?branch=main&label=CI&style=flat-square)](https://github.com/gregdan3/aur-packages/actions/workflows/doppler-cli-bin.yml) [![GitHub release (latest by date)](https://img.shields.io/github/v/release/DopplerHQ/cli?style=flat-square)](https://github.com/DopplerHQ/cli) [![AUR version](https://img.shields.io/aur/version/doppler-cli-bin?style=flat-square)](https://aur.archlinux.org/packages/doppler-cli-bin/)

A CLI utility for [Doppler](https://www.doppler.com/), environment and secrets manager.

### nodejs-markmap-cli

[![GitHub Workflow Status](https://img.shields.io/github/actions/workflow/status/gregdan3/aur-packages/nodejs-markmap-cli.yml?branch=main&label=CI&style=flat-square)](https://github.com/gregdan3/aur-packages/actions/workflows/nodejs-markmap-cli.yml) [![NPM release (latest by date)](https://img.shields.io/npm/v/markmap-cli?style=flat-square)](https://www.npmjs.com/package/markmap-cli/v/latest) [![AUR version](https://img.shields.io/aur/version/nodejs-markmap-cli?style=flat-square)](https://aur.archlinux.org/packages/nodejs-markmap-cli/)

Create markmaps (mindmaps from markdown) from CLI

### ttf-unifont-csur

[![GitHub Workflow Status](https://img.shields.io/github/actions/workflow/status/gregdan3/aur-packages/ttf-unifont-csur.yml?branch=main&label=CI&style=flat-square)](https://github.com/gregdan3/aur-packages/actions/workflows/ttf-unifont-csur.yml) [![Upstream release (latest by date)](https://img.shields.io/badge/Upstream-Not%20Retrievable-lightgray)](https://unifoundry.com/unifont/index.html) [![AUR version](https://img.shields.io/aur/version/ttf-unifont-csur?style=flat-square)](https://aur.archlinux.org/packages/ttf-unifont-csur/)

TrueType part of the GNU Unifont containing Michael Everson's ConScript Unicode Registry (CSUR) Private Use Area (PUA) glyphs

## TODO

- Templating. The only variables, once the `PKGBUILD` is configured and the `.SRCINFO` is generated, are the version fetch command and the name/dir of the package.

## Thanks

Big thanks to GitHub Actions, which has made it easy for me to maintain all these packages with automation.
