Reproduction steps:
* Install a version of `npm` >= 7.0.0 (when `--strict-peer-deps` flag was introduced to easily check for this class of error)
* Run `npm install --strict-peer-deps` in this folder

Observe:
```
npm ERR! code ERESOLVE
npm ERR! ERESOLVE unable to resolve dependency tree
npm ERR!
npm ERR! While resolving: react-spring-test@0.0.1
npm ERR! Found: react-konva@17.0.2-5
npm ERR! node_modules/react-konva
npm ERR!   react-konva@"^17.0.2-5" from the root project
npm ERR!
npm ERR! Could not resolve dependency:
npm ERR! peer react-konva@"^16.8.0  || ^17.0.0" from @react-spring/konva@9.4.4
npm ERR! node_modules/@react-spring/konva
npm ERR!   @react-spring/konva@"^9.4.4" from the root project
npm ERR!
npm ERR! Fix the upstream dependency conflict, or retry
npm ERR! this command with --no-strict-peer-deps, --force, or --legacy-peer-deps
npm ERR! to accept an incorrect (and potentially broken) dependency resolution.
npm ERR!
npm ERR! See /Users/davidkettler/.npm/eresolve-report.txt for a full report.

npm ERR! A complete log of this run can be found in:
npm ERR!     /Users/davidkettler/.npm/_logs/2022-03-16T22_01_41_342Z-debug-0.log
```
