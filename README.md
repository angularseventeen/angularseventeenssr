Wed Feb 14 06:47:16 PM EST 2024

# Angular Seventeen


This project is live at [https://angularseventeen.github.io](https://angularseventeen.github.io "Seventeen!") thanks to Github.

```bash
System Memory
               total        used        free      shared  buff/cache   available
Mem:            15Gi       3.7Gi       1.3Gi       599Mi        11Gi        11Gi
Swap:          8.0Gi       1.3Gi       6.7Gi
System Storage
415M	.
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
    

Angular CLI: 17.1.3
Node: 20.11.1
Package Manager: yarn 1.22.21
OS: linux x64

Angular: 17.2.0
... animations, common, compiler, compiler-cli, core, forms
... platform-browser, platform-browser-dynamic, platform-server
... router

Package                         Version
---------------------------------------------------------
@angular-devkit/architect       0.1701.3
@angular-devkit/build-angular   17.1.3
@angular-devkit/core            17.1.3
@angular-devkit/schematics      17.1.3
@angular/cli                    17.1.3
@angular/ssr                    17.1.3
@schematics/angular             17.1.3
rxjs                            7.8.1
typescript                      5.2.2
zone.js                         0.14.2
    
Done in 0.43s.
yarn install v1.22.21
[1/4] Resolving packages...
success Already up-to-date.
Done in 0.28s.
```
```bash
Latest version:     1.0.30001587
Installed version:  1.0.30001587
caniuse-lite is up to date
caniuse-lite has been successfully updated

No target browser changes
```
```bash
yarn run v1.22.21
$ ng build --configuration production --output-path docs --output-hashing none --stats-json true --subresource-integrity true --verbose true
- Building...


  polyfills.js  32.7kb


  polyfills.server.mjs  261.1kb

● [DEBUG] Lookbehind assertions in regular expressions are not available in the configured target environment ("chrome120.0", "edge120.0", "firefox115.0", "ios16.0", "node20.9.0", "safari16.0" + 5 overrides) [unsupported-regexp]

    node_modules/critters/dist/critters.mjs:1308:30:
      1308 │           sel = sel.replace(/(?<!\\)::?[a-z-]+(?![a-z-(])/gi, ''...
           ╵                               ~~~

  This regular expression literal has been converted to a "new RegExp()" constructor to avoid generating code with a syntax error. However, you will need to include a polyfill for "RegExp" for your code to have the correct behavior at run-time.

● [DEBUG] This call to "require" will not be bundled because the argument is not a string literal [unsupported-require-call]

    node_modules/express/lib/view.js:72:13:
      72 │     var fn = require(mod).__express;
         ╵              ~~~~~~~


  main.js  207.7kb


  server.mjs                 1.0mb ⚠️
  chunk-32ZQW4YO.mjs       503.3kb
  chunk-5X7FPWIP.mjs        19.7kb
  chunk-O73ZHKXN.mjs        11.8kb
  chunk-VVCT4QZE.mjs         2.5kb
  render-utils.server.mjs    1.4kb
  main.server.mjs            149b 

Browser bundles        
Initial chunk files     | Names               |  Raw size | Estimated transfer size
main.js                 | main                | 207.70 kB |                57.27 kB
polyfills.js            | polyfills           |  32.69 kB |                10.59 kB
styles.css              | styles              |   0 bytes |                 0 bytes

                        | Initial total       | 240.39 kB |                67.86 kB


Server bundles         
Initial chunk files     | Names               |  Raw size
server.mjs              | server              |   1.05 MB |                        
chunk-32ZQW4YO.mjs      | -                   | 503.32 kB |                        
polyfills.server.mjs    | polyfills.server    | 261.14 kB |                        
chunk-5X7FPWIP.mjs      | -                   |  19.74 kB |                        
chunk-VVCT4QZE.mjs      | -                   |   2.48 kB |                        
render-utils.server.mjs | render-utils.server |   1.42 kB |                        
main.server.mjs         | main.server         | 149 bytes |                        

Lazy chunk files        | Names               |  Raw size
chunk-O73ZHKXN.mjs      | xhr2                |  11.80 kB |                        

Prerendered 1 static route.
Output location: /home/kushal/src/angular/angularseventeen/docs

Application bundle generation complete. [12.531 seconds]
Done in 13.29s.
```
Wed Feb 14 06:48:06 PM EST 2024
yarn version v1.22.21
info Current version: 0.0.273
info New version: 0.0.274
Done in 0.12s.
