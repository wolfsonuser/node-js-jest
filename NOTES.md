$ npm install
npm WARN old lockfile 
npm WARN old lockfile The package-lock.json file was created with an old version of npm,
npm WARN old lockfile so supplemental metadata must be fetched from the registry.
npm WARN old lockfile
npm WARN old lockfile This is a one-time fix-up, please be patient...
npm WARN old lockfile
npm WARN deprecated set-value@2.0.0: Critical bug fixed in v3.0.1, please upgrade to the latest version.
npm WARN deprecated ini@1.3.5: Please update to ini >=1.3.6 to avoid a prototype pollution issue
npm WARN deprecated set-value@0.4.3: Critical bug fixed in v3.0.1, please upgrade to the latest version.
npm WARN deprecated request-promise-native@1.0.8: request-promise-native has been deprecated because it extends the now deprecated request package, see https://github.com/request/request/issues/3142
npm WARN deprecated urix@0.1.0: Please see https://github.com/lydell/urix#deprecated
npm WARN deprecated har-validator@5.1.3: this library is no longer supported
npm WARN deprecated mixin-deep@1.3.1: Critical bug fixed in v2.0.1, please upgrade to the latest version.
npm WARN deprecated resolve-url@0.2.1: https://github.com/lydell/resolve-url#deprecated
npm WARN deprecated chokidar@2.0.4: Chokidar 2 will break on node v14+. Upgrade to chokidar 3 with 15x less dependencies.     
npm WARN deprecated debug@3.2.6: Debug versions >=3.2.0 <3.2.7 || >=4 <4.3.1 have a low-severity ReDos regression when used in a Node.js environment. It is recommended you upgrade to 3.2.7 or 4.3.1. (https://github.com/visionmedia/debug/issues/797)    
npm WARN deprecated sane@4.1.0: some dependency vulnerabilities fixed, support for node < 10 dropped, and newer ECMAScript syntax/features added
npm WARN deprecated debug@4.1.1: Debug versions >=3.2.0 <3.2.7 || >=4 <4.3.1 have a low-severity ReDos regression when used in a Node.js environment. It is recommended you upgrade to 3.2.7 or 4.3.1. (https://github.com/visionmedia/debug/issues/797)    
npm WARN deprecated uuid@3.4.0: Please upgrade  to version 7 or higher.  Older versions may use Math.random() in certain circumstances, which is known to be problematic.  See https://v8.dev/blog/math-random for details.
npm WARN deprecated @babel/polyfill@7.2.5: ��� This package has been deprecated in favor of separate inclusion of a polyfill and regenerator-runtime (when needed). See the @babel/polyfill docs (https://babeljs.io/docs/en/babel-polyfill) for more information.
npm WARN deprecated request@2.88.2: request has been deprecated, see https://github.com/request/request/issues/3142
npm WARN deprecated mkdirp@0.5.1: Legacy versions of mkdirp are no longer supported. Please update to mkdirp 1.x. (Note that the API surface has changed to use Promises in 1.x.)
npm WARN deprecated core-js@2.6.1: core-js@<3.3 is no longer maintained and not recommended for usage due to the number of issues. Because of the V8 engine whims, feature detection in old core-js versions could cause a slowdown up to 100x even if nothing is polyfilled. Please, upgrade your dependencies to the actual version of core-js.

added 860 packages, and audited 861 packages in 2m

20 packages are looking for funding
  run `npm fund` for details

  35 vulnerabilities (22 moderate, 9 high, 4 critical)

  To address issues that do not require attention, run:
    npm audit fix

    To address all issues (including breaking changes), run:
      npm audit fix --force

      Run `npm audit` for details.

      wolfsonuser52nv53c@DESKTOP-52NV53C MINGW64 ~/GITHUB/node-js-jest (master)
      $ npm test

      > node-babel-server@1.0.0 test
      > jest --config ./jest.config.json

      Browserslist: caniuse-lite is outdated. Please run next command `npm update caniuse-lite browserslist`
      Browserslist: caniuse-lite is outdated. Please run next command `npm update caniuse-lite browserslist`
       PASS  src/call-my-function.spec.js
        PASS  src/spec.js

	Test Suites: 2 passed, 2 total
	Tests:       2 passed, 2 total
	Snapshots:   0 total
	Time:        5.597s
	Ran all test suites.

	wolfsonuser52nv53c@DESKTOP-52NV53C MINGW64 ~/GITHUB/node-js-jest (master)


## ===================================================================

### after running npm audit fix (no --force)


wolfsonuser52nv53c@DESKTOP-52NV53C MINGW64 ~/GITHUB/node-js-jest (master)
$ npm audit fix
npm WARN audit fix tar@4.4.1 node_modules/fsevents/node_modules/tar
npm WARN audit fix tar@4.4.1 is a bundled dependency of
npm WARN audit fix tar@4.4.1 fsevents@1.2.4 at node_modules/fsevents
npm WARN audit fix tar@4.4.1 It cannot be fixed automatically.
npm WARN audit fix tar@4.4.1 Check for updates to the fsevents package.
npm WARN audit fix ini@1.3.5 node_modules/fsevents/node_modules/ini
npm WARN audit fix ini@1.3.5 is a bundled dependency of
npm WARN audit fix ini@1.3.5 fsevents@1.2.4 at node_modules/fsevents
npm WARN audit fix ini@1.3.5 It cannot be fixed automatically.
npm WARN audit fix ini@1.3.5 Check for updates to the fsevents package.
npm WARN audit fix minimist@1.2.0 node_modules/fsevents/node_modules/rc/node_modules/minimist
npm WARN audit fix minimist@1.2.0 is a bundled dependency of
npm WARN audit fix minimist@1.2.0 fsevents@1.2.4 at node_modules/fsevents
npm WARN audit fix minimist@1.2.0 It cannot be fixed automatically.
npm WARN audit fix minimist@1.2.0 Check for updates to the fsevents package.
npm WARN audit fix minimist@0.0.8 node_modules/fsevents/node_modules/minimist
npm WARN audit fix minimist@0.0.8 is a bundled dependency of
npm WARN audit fix minimist@0.0.8 fsevents@1.2.4 at node_modules/fsevents
npm WARN audit fix minimist@0.0.8 It cannot be fixed automatically.
npm WARN audit fix minimist@0.0.8 Check for updates to the fsevents package.
npm WARN audit fix mkdirp@0.5.1 node_modules/fsevents/node_modules/mkdirp
npm WARN audit fix mkdirp@0.5.1 is a bundled dependency of
npm WARN audit fix mkdirp@0.5.1 fsevents@1.2.4 at node_modules/fsevents
npm WARN audit fix mkdirp@0.5.1 It cannot be fixed automatically.
npm WARN audit fix mkdirp@0.5.1 Check for updates to the fsevents package.
npm WARN deprecated request-promise-native@1.0.9: request-promise-native has been deprecated because it extends the now deprecated request package, see https://github.com/request/request/issues/3142
npm WARN deprecated har-validator@5.1.5: this library is no longer supported
npm WARN deprecated chokidar@2.1.8: Chokidar 2 will break on node v14+. Upgrade to chokidar 3 with 15x less dependencies.     

added 134 packages, removed 100 packages, changed 240 packages, and audited 895 packages in 40s

22 packages are looking for funding
  run `npm fund` for details

# npm audit report

ansi-regex  >2.1.1 <5.0.1
Severity: moderate
 Inefficient Regular Expression Complexity in chalk/ansi-regex - https://github.com/advisories/GHSA-93q8-gq69-wqmw
fix available via `npm audit fix --force`
Will install jest@27.4.3, which is a breaking change
node_modules/ansi-regex
node_modules/string-length/node_modules/ansi-regex
  strip-ansi  4.0.0 - 5.2.0
  Depends on vulnerable versions of ansi-regex
  node_modules/string-length/node_modules/strip-ansi
  node_modules/strip-ansi
    string-length  2.0.0 - 3.1.0
    Depends on vulnerable versions of strip-ansi
    node_modules/string-length
      @jest/reporters  <=26.4.0
      Depends on vulnerable versions of node-notifier
      Depends on vulnerable versions of string-length
      node_modules/@jest/reporters
        @jest/core  <=25.5.4
        Depends on vulnerable versions of @jest/reporters
        node_modules/@jest/core
          jest  24.2.0-alpha.0 - 25.5.4
          Depends on vulnerable versions of @jest/core
          Depends on vulnerable versions of jest-cli
          node_modules/jest
          jest-cli  24.2.0-alpha.0 - 25.5.4
          Depends on vulnerable versions of @jest/core
          node_modules/jest-cli
      jest-watcher  <=26.0.0-alpha.2
      Depends on vulnerable versions of string-length
      node_modules/jest-watcher
    string-width  2.1.0 - 4.1.0
    Depends on vulnerable versions of strip-ansi
    node_modules/string-width
      widest-line  2.0.0 - 2.0.1
      Depends on vulnerable versions of string-width
      node_modules/widest-line
        boxen  1.3.0 - 3.2.0
        Depends on vulnerable versions of widest-line
        node_modules/boxen

glob-parent  <5.1.2
Severity: high
Regular expression denial of service - https://github.com/advisories/GHSA-ww39-953v-wcq6
fix available via `npm audit fix --force`
Will install nodemon@2.0.15, which is a breaking change
node_modules/glob-parent
  chokidar  1.0.0-rc1 - 2.1.8
  Depends on vulnerable versions of glob-parent
  node_modules/chokidar
    nodemon  1.4.2 - 1.19.4
    Depends on vulnerable versions of chokidar
    node_modules/nodemon

node-notifier  <8.0.1
Severity: moderate
OS Command Injection in node-notifier - https://github.com/advisories/GHSA-5fw9-fq32-wv5p
fix available via `npm audit fix --force`
Will install jest@27.4.3, which is a breaking change
node_modules/node-notifier
  @jest/reporters  <=26.4.0
  Depends on vulnerable versions of node-notifier
  Depends on vulnerable versions of string-length
  node_modules/@jest/reporters
    @jest/core  <=25.5.4
    Depends on vulnerable versions of @jest/reporters
    node_modules/@jest/core
      jest  24.2.0-alpha.0 - 25.5.4
      Depends on vulnerable versions of @jest/core
      Depends on vulnerable versions of jest-cli
      node_modules/jest
      jest-cli  24.2.0-alpha.0 - 25.5.4
      Depends on vulnerable versions of @jest/core
      node_modules/jest-cli

15 vulnerabilities (12 moderate, 3 high)

To address issues that do not require attention, run:
  npm audit fix

To address all issues (including breaking changes), run:
  npm audit fix --force



## =====================================================================

### after npm audit fix --force:

wolfsonuser52nv53c@DESKTOP-52NV53C MINGW64 ~/GITHUB/node-js-jest (master)
$ git commit -m "Run npm audit fix no --force"
[master c0fcd94] Run npm audit fix no --force
 2 files changed, 6907 insertions(+), 7148 deletions(-)

wolfsonuser52nv53c@DESKTOP-52NV53C MINGW64 ~/GITHUB/node-js-jest (master)
$ npm audit fix --force
npm WARN using --force Recommended protections disabled.
npm WARN audit Updating nodemon to 2.0.15,which is a SemVer major change.
npm WARN audit Updating jest to 27.4.3,which is a SemVer major change.   

added 65 packages, removed 319 packages, changed 155 packages, and audited 641 packages in 32s

33 packages are looking for funding
  run `npm fund` for details

found 0 vulnerabilities

wolfsonuser52nv53c@DESKTOP-52NV53C MINGW64 ~/GITHUB/node-js-jest (master)

