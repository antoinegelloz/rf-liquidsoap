# CHANGELOG.md

## [2.12.2](https://github.com/antoinegelloz/rf-liquidsoap/compare/v2.12.1...v2.12.2) (2026-06-22)


### Bug Fixes

* release ([44e6890](https://github.com/antoinegelloz/rf-liquidsoap/commit/44e689008a899eb1eb2041402050b2dbd06acc39))
* release ([71731f4](https://github.com/antoinegelloz/rf-liquidsoap/commit/71731f426c4c62a209c247c3140d683491d7172d))

## [2.12.1](https://github.com/antoinegelloz/rf-liquidsoap/compare/v2.12.0...v2.12.1) (2026-06-22)


### Bug Fixes

* release ([17924b3](https://github.com/antoinegelloz/rf-liquidsoap/commit/17924b353c68ba14a35261303b9475aaf2df58b1))

## [2.12.0](https://github.com/antoinegelloz/rf-liquidsoap/compare/v2.11.0...v2.12.0) (2026-06-22)


### Features

* wip ([f6f7af3](https://github.com/antoinegelloz/rf-liquidsoap/commit/f6f7af3ef61d995f4f37fa2071ddd75bc1dc3b86))

## [2.11.0](https://github.com/antoinegelloz/rf-liquidsoap/compare/v2.10.0...v2.11.0) (2026-06-22)


### Features

* **CI:** add PR pre-release artifacts ([dd5ac6b](https://github.com/antoinegelloz/rf-liquidsoap/commit/dd5ac6b6b75dd3c330340d970c03d0da742dc1b8))
* **ci:** add PR pre-release prototype ([abc88a4](https://github.com/antoinegelloz/rf-liquidsoap/commit/abc88a47dc3426d571ac50bb453c3d33e51efc76))
* **CI:** add yamllint ([f333753](https://github.com/antoinegelloz/rf-liquidsoap/commit/f33375393668cddc1e8f9c5c1bb87d344524bd49))
* **CI:** add yamllint ([a45b51f](https://github.com/antoinegelloz/rf-liquidsoap/commit/a45b51fc724dc4974a418aa882cd2c6f1d75711d))
* **CI:** improve the release workflow ([75a7462](https://github.com/antoinegelloz/rf-liquidsoap/commit/75a74625b6ddce61529e86ab530c4c5c81f520af))
* **CI:** improve the release workflow ([6efbe8a](https://github.com/antoinegelloz/rf-liquidsoap/commit/6efbe8ad838b2b18232e58af440a5211c717ef90))


### Bug Fixes

* typo in GREETINGS.md file ([475ee33](https://github.com/antoinegelloz/rf-liquidsoap/commit/475ee33ac5bfb229e1734691d5695eef6b50a34e))
* typo in GREETINGS.md file ([cefdc3c](https://github.com/antoinegelloz/rf-liquidsoap/commit/cefdc3cf2e0cd36e47b2c3db1dbdb95c1979fedd))
* typo in README.md file ([4700de2](https://github.com/antoinegelloz/rf-liquidsoap/commit/4700de2119e7963db99d2f4beca5366321408511))
* use liquidsoap-prettier v1.8.3 to format files ([f753e28](https://github.com/antoinegelloz/rf-liquidsoap/commit/f753e281bdb25bcae8b23716946e032b3b86f355))
* use liquidsoap-prettier v1.8.3 to format files ([a88556c](https://github.com/antoinegelloz/rf-liquidsoap/commit/a88556ce775d978fc40305c332924a54bd8fb533))

### [2.0.9](https://www.github.com/radiofrance/rf-liquidsoap/compare/v2.0.6...v2.0.9) (2025-09-30)

- bump(config): migrate config renovate.json
- chore(deps): pin savonet/liquidsoap docker tag to a546c25
- Change ffmpeg image
- Add dashboard with cpu usage per thread
- clean: reindent docker-compose
- Assign named clocks
- fix: remove a typo in the Makefile
- Drop use of latency metrics
- Use only one queue
- fix(settings): keep one fast queue to protect clocked threads
- Set interleaved to false
- feat(liquidsoap): upgrade liquidsoap to fix segfaults and memleaks
- Cleanup top-level variable overrides
- Use docker-compose image for tests
- Updates for 2.4.x APIs

### [2.0.6](https://www.github.com/radiofrance/rf-liquidsoap/compare/v2.0.2...v2.0.6) (2025-05-27)

- bump(config): migrate renovate config
- chore(deps): pin savonet/liquidsoap docker tag to a546c25
- Change ffmpeg image
- Add dashboard with cpu usage per thread
- Assign named clocks
- Drop use of latency metrics
- Use only one queue
- fix(settings): keep one fast queue to protect clocked threads
- Set interleaved to false
- feat(liquidsoap): upgrade liquidsoap to fix segfaults and memleaks

### [2.0.2](https://www.github.com/radiofrance/rf-liquidsoap/compare/v2.0.1...v2.0.2) (2024-03-12)

Features:

- upgrade liquidsoap to v2.2.4. Includes a memory leak fix on srt sources

Breaking changes:

- rename fdkaac profile to libfkd_aac to match real codec names

Bugfix :

- replace `aac_he` profile with `aac_low` for default aac codec since he_aac
  isn't supported
- fix fdkaac profiles names to match real codec names

### [2.0.1](https://www.github.com/radiofrance/rf-liquidsoap/compare/v2.0.0...v2.0.1) (2024-01-08)

Features:

- upgrade liquidsoap to v2.2.3

## 2.0.0 (2023-11-06)

Features:

- split scripts for different liquidsoap usages, transcoder (to produce a radio
  stream) and streamer (to send audio to a transcoder with SRT, and serve
  playlists or network sources - WIP).
- add surround profiles for 5.1 streaming.
- add insane AAC quality profile (aac/fdk_aac lc 320kbps).
- support disabling HLS or Icecast outputs completely (removing all qualities).
- remove test file and use example configs by default for tests.
- upgrade liquidsoap to v2.2.2
- add new srtcaller containers in docker-compose.yml, one to stream local files
  with ffmpeg, another one to stream a local playlist with liquidsoap and a m3u
  file.

Breaking changes:

- some variables have been renamed in the configuration file.
- a new function must be declared in the configuration file to select a channel
  layout (stereo or surround).
- scripts paths have changed, be careful if you use the scripts folder directly.
