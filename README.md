Reproduction steps:
* Install a version of `npm` >= 7.0.0 (when `--strict-peer-deps` flag was introduced to easily check for this class of error)
* Run `npm install --strict-peer-deps` in this folder

Observe:
```
npm ERR! code ERESOLVE
npm ERR! ERESOLVE could not resolve
npm ERR!
npm ERR! While resolving: react-spring@9.4.4
npm ERR! Found: react@16.8.6
npm ERR! node_modules/react-spring/node_modules/react
npm ERR!   peer react@"^16.8.0  || ^17.0.0" from @react-spring/konva@9.4.4
npm ERR!   node_modules/react-spring/node_modules/@react-spring/konva
npm ERR!     @react-spring/konva@"~9.4.4" from react-spring@9.4.4
npm ERR!     node_modules/react-spring
npm ERR!       react-spring@"^9.4.4" from the root project
npm ERR!   peer react@"16.8.x" from react-konva@16.8.6
npm ERR!   node_modules/react-spring/node_modules/react-konva
npm ERR!     peer react-konva@"^16.8.0  || ^17.0.0" from @react-spring/konva@9.4.4
npm ERR!     node_modules/react-spring/node_modules/@react-spring/konva
npm ERR!       @react-spring/konva@"~9.4.4" from react-spring@9.4.4
npm ERR!       node_modules/react-spring
npm ERR!         react-spring@"^9.4.4" from the root project
npm ERR!   1 more (react-dom)
npm ERR!
npm ERR! Could not resolve dependency:
npm ERR! @react-spring/native@"~9.4.4" from react-spring@9.4.4
npm ERR! node_modules/react-spring
npm ERR!   react-spring@"^9.4.4" from the root project
npm ERR!
npm ERR! Conflicting peer dependency: react@17.0.2
npm ERR! node_modules/react
npm ERR!   peer react@"17.0.2" from react-native@0.67.3
npm ERR!   node_modules/react-native
npm ERR!     peer react-native@">=0.58" from @react-spring/native@9.4.4
npm ERR!     node_modules/@react-spring/native
npm ERR!       @react-spring/native@"~9.4.4" from react-spring@9.4.4
npm ERR!       node_modules/react-spring
npm ERR!         react-spring@"^9.4.4" from the root project
npm ERR!
npm ERR! Fix the upstream dependency conflict, or retry
npm ERR! this command with --no-strict-peer-deps, --force, or --legacy-peer-deps
npm ERR! to accept an incorrect (and potentially broken) dependency resolution.
```
