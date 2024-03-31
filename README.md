Sat Mar 30 08:06:42 PM EDT 2024

# Angular Seventeen


This project is live at [https://angularseventeen.github.io](https://angularseventeen.github.io "Seventeen!") thanks to Github.

```bash
System Memory
               total        used        free      shared  buff/cache   available
Mem:            15Gi       2.1Gi       2.8Gi       310Mi        11Gi        13Gi
Swap:          8.0Gi          0B       8.0Gi
System Storage
415M	.
```
```bash
yarn run v1.22.22
$ ng version

     _                      _                 ____ _     ___
    / \   _ __   __ _ _   _| | __ _ _ __     / ___| |   |_ _|
   / △ \ | '_ \ / _` | | | | |/ _` | '__|   | |   | |    | |
  / ___ \| | | | (_| | |_| | | (_| | |      | |___| |___ | |
 /_/   \_\_| |_|\__, |\__,_|_|\__,_|_|       \____|_____|___|
                |___/
    

Angular CLI: 17.3.2
Node: 20.12.0
Package Manager: yarn 1.22.22
OS: linux x64

Angular: 17.3.2
... animations, cli, common, compiler, compiler-cli, core, forms
... platform-browser, platform-browser-dynamic, platform-server
... router, ssr

Package                         Version
---------------------------------------------------------
@angular-devkit/architect       0.1703.2
@angular-devkit/build-angular   17.3.2
@angular-devkit/core            17.3.2
@angular-devkit/schematics      17.3.2
@schematics/angular             17.3.2
rxjs                            7.8.1
typescript                      5.2.2
zone.js                         0.14.2
    
Done in 0.48s.
yarn install v1.22.22
[1/4] Resolving packages...
success Already up-to-date.
Done in 0.27s.
```
```bash
Latest version:     1.0.30001600
Installed version:  1.0.30001600
caniuse-lite is up to date
caniuse-lite has been successfully updated

No target browser changes
```
```bash
yarn run v1.22.22
$ ng build --configuration production --output-path docs --output-hashing none --stats-json true --subresource-integrity true --verbose true
- Building...


  polyfills.js  32.7kb


  polyfills.server.mjs  261.1kb

● [DEBUG] Lookbehind assertions in regular expressions are not available in the configured target environment ("chrome121.0", "edge121.0", "firefox115.0", "ios16.0", "node20.9.0", "safari16.0" + 5 overrides) [unsupported-regexp]

    node_modules/critters/dist/critters.mjs:1341:51:
      1341 │ ...nst crittersComment = rule.text.match(/^(?<!\! )critters:(.*)/);
           ╵                                             ~~~

  This regular expression literal has been converted to a "new RegExp()" constructor to avoid generating code with a syntax error. However, you will need to include a polyfill for "RegExp" for your code to have the correct behavior at run-time.

● [DEBUG] Lookbehind assertions in regular expressions are not available in the configured target environment ("chrome121.0", "edge121.0", "firefox115.0", "ios16.0", "node20.9.0", "safari16.0" + 5 overrides) [unsupported-regexp]

    node_modules/critters/dist/critters.mjs:1399:30:
      1399 │           sel = sel.replace(/(?<!\\)::?[a-z-]+(?![a-z-(])/gi, ''...
           ╵                               ~~~

  This regular expression literal has been converted to a "new RegExp()" constructor to avoid generating code with a syntax error. However, you will need to include a polyfill for "RegExp" for your code to have the correct behavior at run-time.

● [DEBUG] This call to "require" will not be bundled because the argument is not a string literal [unsupported-require-call]

    node_modules/express/lib/view.js:72:13:
      72 │     var fn = require(mod).__express;
         ╵              ~~~~~~~


  main.js  209.5kb


  server.mjs                 1.1mb ⚠️
  chunk-OUHCZT45.mjs       505.3kb
  chunk-IZPY4UOV.mjs        19.7kb
  chunk-O73ZHKXN.mjs        11.8kb
  chunk-VVCT4QZE.mjs         2.5kb
  render-utils.server.mjs    1.4kb
  main.server.mjs            149b 

Browser bundles        
Initial chunk files     | Names               |  Raw size | Estimated transfer size
main.js                 | main                | 209.52 kB |                57.73 kB
polyfills.js            | polyfills           |  32.69 kB |                10.59 kB
styles.css              | styles              |   0 bytes |                 0 bytes

                        | Initial total       | 242.22 kB |                68.33 kB


Server bundles         
Initial chunk files     | Names               |  Raw size
server.mjs              | server              |   1.05 MB |                        
chunk-OUHCZT45.mjs      | -                   | 505.26 kB |                        
polyfills.server.mjs    | polyfills.server    | 261.14 kB |                        
chunk-IZPY4UOV.mjs      | -                   |  19.68 kB |                        
chunk-VVCT4QZE.mjs      | -                   |   2.48 kB |                        
render-utils.server.mjs | render-utils.server |   1.42 kB |                        
main.server.mjs         | main.server         | 149 bytes |                        

Lazy chunk files        | Names               |  Raw size
chunk-O73ZHKXN.mjs      | xhr2                |  11.80 kB |                        

Prerendered 1 static route.
Output location: /home/kushal/src/angular/angularseventeen/docs

Application bundle generation complete. [8.280 seconds]

Done in 8.89s.
```
Sat Mar 30 08:07:03 PM EDT 2024
yarn version v1.22.22
info Current version: 0.0.370
info New version: 0.0.371
Done in 0.11s.
