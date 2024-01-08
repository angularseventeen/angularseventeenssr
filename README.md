Mon Jan  8 12:18:53 PM EST 2024

# Angular Seventeen


This project is live at [https://angularseventeen.github.io](https://angularseventeen.github.io "Seventeen!") thanks to Github.

```bash
System Memory
               total        used        free      shared  buff/cache   available
Mem:            15Gi       1.9Gi       2.7Gi       301Mi        11Gi        13Gi
Swap:          8.0Gi          0B       8.0Gi
System Storage
401M	.
```
```bash
yarn run v1.22.21
$ ng version

     _                      _                 ____ _     ___
    / \   _ __   __ _ _   _| | __ _ _ __     / ___| |   |_ _|
   / △ \ | '_ \ / _` | | | | |/ _` | '__|   | |   | |    | |
  / ___ \| | | | (_| | |_| | | (_| | |      | |___| |___ | |
 /_/   \_\_| |_|\__, |\__,_|_|\__,_|_|       \____|_____|___|
                |___/
    

Angular CLI: 17.0.9
Node: 20.10.0
Package Manager: yarn 1.22.21
OS: linux x64

Angular: 17.0.8
... animations, common, compiler, compiler-cli, core, forms
... platform-browser, platform-browser-dynamic, platform-server
... router

Package                         Version
---------------------------------------------------------
@angular-devkit/architect       0.1700.9
@angular-devkit/build-angular   17.0.9
@angular-devkit/core            17.0.9
@angular-devkit/schematics      17.0.9
@angular/cli                    17.0.9
@angular/ssr                    17.0.9
@schematics/angular             17.0.9
rxjs                            7.8.1
typescript                      5.2.2
zone.js                         0.14.2
    
Done in 0.50s.
yarn install v1.22.21
[1/4] Resolving packages...
success Already up-to-date.
Done in 0.26s.
```
```bash
Latest version:     1.0.30001576
Installed version:  1.0.30001574
Removing old caniuse-lite from lock file
Installing new caniuse-lite version
$ yarn add -W caniuse-lite
Cleaning package.json dependencies from caniuse-lite
$ yarn remove -W caniuse-lite
caniuse-lite has been successfully updated

No target browser changes
```
```bash
yarn run v1.22.21
$ ng build --configuration production --output-path docs --output-hashing none --stats-json true --subresource-integrity true --verbose true
- Building...


  polyfills.js  32.7kb


  polyfills.server.mjs  261.2kb

● [DEBUG] Lookbehind assertions in regular expressions are not available in the configured target environment ("chrome119.0", "edge119.0", "firefox115.0", "ios16.0", "node20.9.0", "safari16.0" + 5 overrides) [unsupported-regexp]

    node_modules/critters/dist/critters.mjs:1309:30:
      1309 │           sel = sel.replace(/(?<!\\)::?[a-z-]+(?![a-z-(])/gi, ''...
           ╵                               ~~~

  This regular expression literal has been converted to a "new RegExp()" constructor to avoid generating code with a syntax error. However, you will need to include a polyfill for "RegExp" for your code to have the correct behavior at run-time.

● [DEBUG] This call to "require" will not be bundled because the argument is not a string literal [unsupported-require-call]

    node_modules/express/lib/view.js:72:13:
      72 │     var fn = require(mod).__express;
         ╵              ~~~~~~~


  main.js  203.8kb


  server.mjs                 1.1mb ⚠️
  chunk-UBOOE534.mjs       499.6kb
  chunk-RMQTL5WE.mjs        19.7kb
  chunk-53JWIC36.mjs        11.8kb
  chunk-KRLCULJA.mjs         2.5kb
  render-utils.server.mjs    1.4kb
  main.server.mjs            149b 

Prerendered 1 static route.


Initial Chunk Files | Names         |  Raw Size | Estimated Transfer Size
main.js             | main          | 203.84 kB |                56.30 kB
polyfills.js        | polyfills     |  32.69 kB |                10.59 kB
styles.css          | styles        |   0 bytes |                 0 bytes

                    | Initial Total | 236.53 kB |                66.89 kB

Application bundle generation complete. [12.162 seconds]
Done in 12.86s.
```
Mon Jan  8 12:19:24 PM EST 2024
yarn version v1.22.21
info Current version: 0.0.131
info New version: 0.0.132
Done in 0.11s.
