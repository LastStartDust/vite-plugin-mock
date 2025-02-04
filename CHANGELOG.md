# [2.6.0](https://github.com/anncwb/vite-plugin-mock/compare/v2.5.0...v2.6.0) (2021-05-29)

### Bug Fixes

- loss request headers in PROD mode ([#23](https://github.com/anncwb/vite-plugin-mock/issues/23)) ([76302df](https://github.com/anncwb/vite-plugin-mock/commit/76302df9cc5a23fe0ccd001787bffbb4c012cc83)), closes [#15](https://github.com/anncwb/vite-plugin-mock/issues/15)

### Reverts

- revert 2.5.0, fix [#22](https://github.com/anncwb/vite-plugin-mock/issues/22) ([d5ac0d6](https://github.com/anncwb/vite-plugin-mock/commit/d5ac0d68a67f4e4cc568ef1eff12f2ba425553e8))

# [2.5.0](https://github.com/anncwb/vite-plugin-mock/compare/v2.4.0...v2.5.0) (2021-04-06)

### Bug Fixes

- production xhr ([6c94783](https://github.com/anncwb/vite-plugin-mock/commit/6c94783f07b27c6ac58a4642c0e7eddf34b06f1f))
- **eslint warn:** fix some warn ([b44c13b](https://github.com/anncwb/vite-plugin-mock/commit/b44c13b766cda0ee310071e9febeb48d73ef7bde))
- empty TS file in mock folder is error ([669b804](https://github.com/anncwb/vite-plugin-mock/commit/669b804df31f537bf6985b56972b32dd11e20504))

### Features

- add rawResponse option to MockMethod ([#17](https://github.com/anncwb/vite-plugin-mock/issues/17)) ([24775f9](https://github.com/anncwb/vite-plugin-mock/commit/24775f9d7b14d024d90cd36c850a00634341927f)), closes [#16](https://github.com/anncwb/vite-plugin-mock/issues/16)

### Performance Improvements

- perf code ([98b9dbc](https://github.com/anncwb/vite-plugin-mock/commit/98b9dbc64f5c6da815a1f29c6b588fddd5189370))

## [2.4.1](https://github.com/anncwb/vite-plugin-mock/compare/v2.4.0...v2.4.1) (2021-03-30)

### Bug Fixes

- empty TS file in mock folder is error ([669b804](https://github.com/anncwb/vite-plugin-mock/commit/669b804df31f537bf6985b56972b32dd11e20504))

### Performance Improvements

- perf code ([98b9dbc](https://github.com/anncwb/vite-plugin-mock/commit/98b9dbc64f5c6da815a1f29c6b588fddd5189370))

# [2.4.0](https://github.com/anncwb/vite-plugin-mock/compare/v2.3.0...v2.4.0) (2021-03-25)

### Features

- response return headers, close [#10](https://github.com/anncwb/vite-plugin-mock/issues/10) ([bcb7abd](https://github.com/anncwb/vite-plugin-mock/commit/bcb7abd98e8726af6f1721ad021c06028b1ffca7))

## [2.2.4](https://github.com/anncwb/vite-plugin-mock/compare/v2.2.3...v2.2.4) (2021-03-10)

### Features

- support post restful close [#7](https://github.com/anncwb/vite-plugin-mock/issues/7) ([70b51e8](https://github.com/anncwb/vite-plugin-mock/commit/70b51e8738e41a7011e38e942dd2a136e450ae9f))

## [2.2.3](https://github.com/anncwb/vite-plugin-mock/compare/v2.2.0...v2.2.3) (2021-03-10)

### Bug Fixes

- ensure that the URLs of different request methods cannot match close [#6](https://github.com/anncwb/vite-plugin-mock/issues/6) ([361a3eb](https://github.com/anncwb/vite-plugin-mock/commit/361a3eb62874f7a6dce8cdc8add4487302c3ee04))

### Features

- support restful api close [#4](https://github.com/anncwb/vite-plugin-mock/issues/4) ([236393e](https://github.com/anncwb/vite-plugin-mock/commit/236393ef551de32fbba62fbb27f678d4782568ec))

## [2.2.1](https://github.com/anncwb/vite-plugin-mock/compare/v2.2.0...v2.2.1) (2021-03-09)

### Features

- support restful api close [#4](https://github.com/anncwb/vite-plugin-mock/issues/4) ([7a35b1a](https://github.com/anncwb/vite-plugin-mock/commit/7a35b1a3af3bfa8623f1d24f53e71928df20b69b))

# [2.2.0](https://github.com/anncwb/vite-plugin-mock/compare/v2.1.5...v2.2.0) (2021-03-02)

### Features

- add logger option ([66a75ab](https://github.com/anncwb/vite-plugin-mock/commit/66a75ab0ee5a7c8e03987e74f15b50aedd1cc29f))

## [2.1.5](https://github.com/anncwb/vite-plugin-mock/compare/v2.0.0-beta.1...v2.1.5) (2021-02-23)

### Bug Fixes

- correct sourcemap ([2140987](https://github.com/anncwb/vite-plugin-mock/commit/21409876876b845b18b5b006e98292138870a922))
- dev sourcemap ([5834b4f](https://github.com/anncwb/vite-plugin-mock/commit/5834b4f621b25371a7b0246a48fb83b9761afeed))
- fix post proxy error ([d3ae41e](https://github.com/anncwb/vite-plugin-mock/commit/d3ae41e18a5e7adae504457165ba7b34b8ebff6f))

### Features

- support sourcemap ([8c3cd9d](https://github.com/anncwb/vite-plugin-mock/commit/8c3cd9d78a9bd7f87dc7900e9bfe6c753ff3b11f))

### Performance Improvements

- imporve request log ([f9353fd](https://github.com/anncwb/vite-plugin-mock/commit/f9353fdf8149665f984729ab3c7a6749022cfdaf))

# [2.0.0-beta.1](https://github.com/anncwb/vite-plugin-mock/compare/2.0.0-beta.1...v2.0.0-beta.1) (2021-01-03)

### Bug Fixes

- Fix local development post request proxy to https ([7965604](https://github.com/anncwb/vite-plugin-mock/commit/79656046377f501da796d1be9752522a2203d69b))
- remove unnecessary and wrong usage of "try catch" ([815abde](https://github.com/anncwb/vite-plugin-mock/commit/815abde26f8f9a19322916ae01a9896a9aced33a))

### Features

- add request time ([ccbb14a](https://github.com/anncwb/vite-plugin-mock/commit/ccbb14ad623e6549781e5e902819f830a291f13f))

## [1.0.2](https://github.com/anncwb/vite-plugin-mock/compare/1.0.1...1.0.2) (2020-09-14)

### Features

- add examples ([2c5a86b](https://github.com/anncwb/vite-plugin-mock/commit/2c5a86bb75e39b6c7c9e08b1691c0541aeb104d9))

## [1.0.1](https://github.com/anncwb/vite-plugin-mock/compare/58ad7cd57e3fd0daa92e0fc59c00e09cf6ba45ad...1.0.1) (2020-09-14)

### Features

- add supportTs options,Support es6 and commonjs modules in .js folder ([37f83f5](https://github.com/anncwb/vite-plugin-mock/commit/37f83f54c3a34e049f967b0db0ac2ade401cbf58))

### Performance Improvements

- Replace typescript plug-in with a faster esbuild plug-in ([58ad7cd](https://github.com/anncwb/vite-plugin-mock/commit/58ad7cd57e3fd0daa92e0fc59c00e09cf6ba45ad))
