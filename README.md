# phaser3-webpack4-typescript3-mobile-app-template

This is a template project for development of phaser3 mobile web app wrriten with typescript3, and built with webpack4.

# features

WIP

## npm scripts

| command        | description                                                                                                                           |
| -------------- | ------------------------------------------------------------------------------------------------------------------------------------- |
| debug          | Build all for development, and output to directory `build`. define DEBUG = true; not minify js, make source-map, not compress assets) |
| release        | Build all for production, and output to directory `build`.                                                                            |
| start          | Same as `debug`, and run dev server. Access to `127.0.0.1:8080` to watch current app working.                                         |
| publish        | Same as `release`, and copy output to direcory `dist` (is included in this repository, different from build)                          |
| gen-assets-def | Generate definitions(as .ts files) of assets.（WIP: only for raw image assets currently)                                              |
| format         | Format all scripts below `src/scripts`                                                                                                |

## directories

| directory | description                                                                                    |
| --------- | ---------------------------------------------------------------------------------------------- |
| build     | Working directory. This is temporary dir and ignored by this repository.                       |
| dist      | The app ready to publish (built with release config).                                          |
| src       | App sources including html, css, assets(images, sounds, etc), and typescripts(include phaser). |
| webpack   | Build config files with development or production.                                             |

# demo

[Raw result of npm run publish](https://gomachan7.github.io/phaser3-webpack4-typescript3-mobile-app-template/dist/)
