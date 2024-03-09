Sat Mar  9 10:12:57 AM EST 2024

# Angular Seventeen


This project is live at [https://angularseventeen.github.io](https://angularseventeen.github.io "Seventeen!") thanks to Github.

```bash
System Memory
               total        used        free      shared  buff/cache   available
Mem:            15Gi       3.9Gi       1.1Gi       292Mi        10Gi        11Gi
Swap:          8.0Gi       971Mi       7.1Gi
System Storage
394M	.
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
    

Angular CLI: 17.2.3
Node: 20.11.1
Package Manager: yarn 1.22.21
OS: linux x64

Angular: 17.2.4
... animations, common, compiler, compiler-cli, core, forms
... platform-browser, platform-browser-dynamic, platform-server
... router

Package                         Version
---------------------------------------------------------
@angular-devkit/architect       0.1702.3
@angular-devkit/build-angular   17.2.3
@angular-devkit/core            17.2.3
@angular-devkit/schematics      17.2.3
@angular/cli                    17.2.3
@angular/ssr                    17.2.3
@schematics/angular             17.2.3
rxjs                            7.8.1
typescript                      5.2.2
zone.js                         0.14.2
    
Done in 0.54s.
yarn install v1.22.21
[1/4] Resolving packages...
success Already up-to-date.
Done in 0.33s.
```
```bash
Latest version:     1.0.30001596
Installed version:  1.0.30001596
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

● [DEBUG] Lookbehind assertions in regular expressions are not available in the configured target environment ("chrome121.0", "edge121.0", "firefox115.0", "ios16.0", "node20.9.0", "safari16.0" + 5 overrides) [unsupported-regexp]

    node_modules/critters/dist/critters.mjs:1308:30:
      1308 │           sel = sel.replace(/(?<!\\)::?[a-z-]+(?![a-z-(])/gi, ''...
           ╵                               ~~~

  This regular expression literal has been converted to a "new RegExp()" constructor to avoid generating code with a syntax error. However, you will need to include a polyfill for "RegExp" for your code to have the correct behavior at run-time.

● [DEBUG] This call to "require" will not be bundled because the argument is not a string literal [unsupported-require-call]

    node_modules/express/lib/view.js:72:13:
      72 │     var fn = require(mod).__express;
         ╵              ~~~~~~~


  main.js  208.1kb


  server.mjs                 1.0mb ⚠️
  chunk-XZZGI7US.mjs       503.7kb
  chunk-4UTZODQI.mjs        19.7kb
  chunk-O73ZHKXN.mjs        11.8kb
  chunk-VVCT4QZE.mjs         2.5kb
  render-utils.server.mjs    1.4kb
  main.server.mjs            149b 

Browser bundles        
Initial chunk files     | Names               |  Raw size | Estimated transfer size
main.js                 | main                | 208.09 kB |                57.36 kB
polyfills.js            | polyfills           |  32.69 kB |                10.59 kB
styles.css              | styles              |   0 bytes |                 0 bytes

                        | Initial total       | 240.79 kB |                67.95 kB


Server bundles         
Initial chunk files     | Names               |  Raw size
server.mjs              | server              |   1.05 MB |                        
chunk-XZZGI7US.mjs      | -                   | 503.73 kB |                        
polyfills.server.mjs    | polyfills.server    | 261.14 kB |                        
chunk-4UTZODQI.mjs      | -                   |  19.74 kB |                        
chunk-VVCT4QZE.mjs      | -                   |   2.48 kB |                        
render-utils.server.mjs | render-utils.server |   1.42 kB |                        
main.server.mjs         | main.server         | 149 bytes |                        

Lazy chunk files        | Names               |  Raw size
chunk-O73ZHKXN.mjs      | xhr2                |  11.80 kB |                        

Prerendered 1 static route.
Output location: /home/kushal/src/angular/angularseventeen/docs

Application bundle generation complete. [8.778 seconds]
Done in 9.47s.
```
Sat Mar  9 10:13:23 AM EST 2024
yarn version v1.22.21
info Current version: 0.0.342
info New version: 0.0.343
Done in 0.12s.
