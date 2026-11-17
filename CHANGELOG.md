# CHANGELOG.md

## [3.0.0](https://github.com/antoinegelloz/rf-liquidsoap/compare/v2.13.0...v3.0.0) (2026-11-17)


### ⚠ BREAKING CHANGES

* **streamer:** a streamer config defines replaygain_enabled and replaygain_target_lufs.

### Features

* Adding tests running in a container using savonet:liquidsoap ([5e7004b](https://github.com/antoinegelloz/rf-liquidsoap/commit/5e7004be094ef85a3802b3103f616380b9307e9d))
* Adding tests using Github Action ([001a943](https://github.com/antoinegelloz/rf-liquidsoap/commit/001a943af2246715a5b3c5b56b3aa0243fab9bba))
* bump liquidsoap to rolling-release ([e53cb4c](https://github.com/antoinegelloz/rf-liquidsoap/commit/e53cb4c01e6f64c526337576e25781aa9e86a2a0))
* **ci:** add liquidsoap-prettier formatting test ([518ab7b](https://github.com/antoinegelloz/rf-liquidsoap/commit/518ab7bd1f22d61c91a97f27e7e021d45c34c3a7))
* **ci:** add liquidsoap-prettier formatting test ([a519d41](https://github.com/antoinegelloz/rf-liquidsoap/commit/a519d41948891a5ea5109d43733512188687c95d))
* **CI:** add new commitlint job ([e34c8a4](https://github.com/antoinegelloz/rf-liquidsoap/commit/e34c8a44aedeeb29c45d2d062ea276307aa3032d))
* **CI:** add new commitlint job ([7a9e795](https://github.com/antoinegelloz/rf-liquidsoap/commit/7a9e795b3ed2692ec66355a8368cbf83be7e81cf))
* **CI:** add PR pre-release artifacts ([dd5ac6b](https://github.com/antoinegelloz/rf-liquidsoap/commit/dd5ac6b6b75dd3c330340d970c03d0da742dc1b8))
* **CI:** add PR pre-release artifacts ([abc88a4](https://github.com/antoinegelloz/rf-liquidsoap/commit/abc88a47dc3426d571ac50bb453c3d33e51efc76))
* **ci:** add renovate on liquidsoap version ([1fc042c](https://github.com/antoinegelloz/rf-liquidsoap/commit/1fc042c6561afc7fb43fb9e896fc3368a3bbf121))
* **ci:** add renovate on liquidsoap version ([800651a](https://github.com/antoinegelloz/rf-liquidsoap/commit/800651adf02c95876e809360d261b480c9e6e95a))
* **ci:** add sha256 checksum in each release ([28b4c16](https://github.com/antoinegelloz/rf-liquidsoap/commit/28b4c165cf977529cf4b98f0ae0d2dc1aec461d1))
* **CI:** add yamllint ([f333753](https://github.com/antoinegelloz/rf-liquidsoap/commit/f33375393668cddc1e8f9c5c1bb87d344524bd49))
* **CI:** add yamllint ([a45b51f](https://github.com/antoinegelloz/rf-liquidsoap/commit/a45b51fc724dc4974a418aa882cd2c6f1d75711d))
* **CI:** improve the release workflow ([951266f](https://github.com/antoinegelloz/rf-liquidsoap/commit/951266f68eed21074957be7ce82ef25c1fa34a11))
* **ci:** use npm ci instead of manual dependencies management in github action ([ce3506f](https://github.com/antoinegelloz/rf-liquidsoap/commit/ce3506f18dbd3b79fdeafd065ebb223fd694196c))
* **ci:** use npm commands to run validation scripts in github action ([ed9ed01](https://github.com/antoinegelloz/rf-liquidsoap/commit/ed9ed0183380f6fa70cb7fc605351ebb76aff8d7))
* **config:** rename some hls variables ([d7ae2fa](https://github.com/antoinegelloz/rf-liquidsoap/commit/d7ae2fab5b66aa44927bb1ab796dc850580f0b11))
* **docker-compose:** create a surround radio example ([d25e2d7](https://github.com/antoinegelloz/rf-liquidsoap/commit/d25e2d7d52769db52338b82802947b4655064301))
* **docker-compose:** rename source streams ([42d2c67](https://github.com/antoinegelloz/rf-liquidsoap/commit/42d2c67984ea492f862f8342e1bee33d553aa14f))
* **docker-compose:** restream datafruits.fm, p-node, modular-station ([15b5879](https://github.com/antoinegelloz/rf-liquidsoap/commit/15b587952be18440a7ea10b4a16a6dc1e54c20df))
* **docker-compose:** upgrade to liquidsoap v2.2.2 ([1daba41](https://github.com/antoinegelloz/rf-liquidsoap/commit/1daba415f22a8423ff39c6c95d465fa90fb48130))
* **docker-compose:** upgrade to liquidsoap v2.2.3 ([853bb45](https://github.com/antoinegelloz/rf-liquidsoap/commit/853bb450e56b734b1f71f99522385d9d7a79312a))
* **docker-compose:** upgrade to liquidsoap v2.2.3 ([5ee94db](https://github.com/antoinegelloz/rf-liquidsoap/commit/5ee94db6f85a2533debebc781d097a55e223508b))
* **docker-compose:** upgrade to liquidsoap v2.2.4 ([fb3f640](https://github.com/antoinegelloz/rf-liquidsoap/commit/fb3f640640bbc3a404d43ccb4cb79237e61d6b58))
* **docker-compose:** upgrade to liquidsoap v2.2.4 ([0630d1a](https://github.com/antoinegelloz/rf-liquidsoap/commit/0630d1ac33b7408982c6cb9ca542e1056fda6877))
* **docker-compose:** upgrade to liquidsoap v2.2.5 ([7219a0c](https://github.com/antoinegelloz/rf-liquidsoap/commit/7219a0c41733858a3859826d8f67c8631f29f48f))
* **docker-compose:** upgrade to liquidsoap v2.2.5 ([b4c3d64](https://github.com/antoinegelloz/rf-liquidsoap/commit/b4c3d649f1d94d4acb90d39271fa00bc9bacf716))
* **docker:** update liquidsoap to stable release 2.2.0 ([576f83d](https://github.com/antoinegelloz/rf-liquidsoap/commit/576f83d76e398dffa26311bbc23dae4094c1750c))
* **example:** anonymize radio names ([b7be3e5](https://github.com/antoinegelloz/rf-liquidsoap/commit/b7be3e51f464ce81cebd681453b2b5f60d151421))
* **example:** use -re in ffmpeg ([0b19054](https://github.com/antoinegelloz/rf-liquidsoap/commit/0b190546132343a92a131796f1d719043088409d))
* **fallback:** safe blank should be in the auto fallback group ([bc5c84a](https://github.com/antoinegelloz/rf-liquidsoap/commit/bc5c84a29d9dc35723a91884f82bbee8077e05ab))
* **formats:** add "insane" quality ([851f94c](https://github.com/antoinegelloz/rf-liquidsoap/commit/851f94cd01af86218463255103a0349567ea760a))
* **formats:** add insane format everywhere ([a1dd7e3](https://github.com/antoinegelloz/rf-liquidsoap/commit/a1dd7e3f18632d3a6ce30fadb39362e8afa440f7))
* **formats:** replace 5.1 AAC-LC 256kbps with 5.1 AAC-HE 192kbps ([5f608f3](https://github.com/antoinegelloz/rf-liquidsoap/commit/5f608f38cda5a0c3a56c51e2cde9725814ffcf1e))
* **grafana:** add levels in liquidsoap main dashboard ([cf596bd](https://github.com/antoinegelloz/rf-liquidsoap/commit/cf596bd112dc9d832b9eece10344ba10e0e10c35))
* **grafana:** add lufs dashboard ([833e9dc](https://github.com/antoinegelloz/rf-liquidsoap/commit/833e9dc345ee6b213d0e7dbe5f75ff30b74e3b0b))
* **grafana:** add srt input visualizations in liquidsoap dashboard ([b15606a](https://github.com/antoinegelloz/rf-liquidsoap/commit/b15606ac7262ed9663d64a6dbf09e43addad4121))
* **liquidsoap:** update to 2.2.1 ([aa040b3](https://github.com/antoinegelloz/rf-liquidsoap/commit/aa040b3685153742bf513e7a6d3e8836490c8e07))
* **liquidsoap:** update to 2.2.1 ([d61d66f](https://github.com/antoinegelloz/rf-liquidsoap/commit/d61d66fd83b30be8138b3432de4fbffdbe3d66ac))
* **liquidsoap:** upgrade liquidsoap to fix segfaults and memleaks ([#56](https://github.com/antoinegelloz/rf-liquidsoap/issues/56)) ([809804b](https://github.com/antoinegelloz/rf-liquidsoap/commit/809804b7b18d1fb70cfb4ec2961783904752a312))
* **liquidsoap:** upgrade to liquidsoap v2.2.0 ([be47c28](https://github.com/antoinegelloz/rf-liquidsoap/commit/be47c28235370cab8d7df852ca1bef6fe6e89c3e))
* **liquidsoap:** upgrade to liquidsoap v2.2.x ([bfa8bcb](https://github.com/antoinegelloz/rf-liquidsoap/commit/bfa8bcb1366428765ac7fc0b34f34ae5611b0ad8))
* **logs:** prevent multiline logs ([ca84004](https://github.com/antoinegelloz/rf-liquidsoap/commit/ca84004ab1e7e0aee1ae350002a24eb93fcb3306))
* **makefile:** add a simple makefile to facilitate development ([0810796](https://github.com/antoinegelloz/rf-liquidsoap/commit/0810796aa5ba9f77ce7066e9377c7b8c9f8bc0cd))
* **Makefile:** add liquidsoap-prettier in makefile ([98e6bc1](https://github.com/antoinegelloz/rf-liquidsoap/commit/98e6bc1b258740f0557acfc85ac1a1827f18ae0d))
* **Makefile:** create make artifact command ([0f74050](https://github.com/antoinegelloz/rf-liquidsoap/commit/0f7405016d77f50cbc80bbbc24ac70a8cceb6fa9))
* **metrics:** change metric refresh time from 0.1s to 1.0s ([84d7379](https://github.com/antoinegelloz/rf-liquidsoap/commit/84d73790faf1e56274e9d7fa9a4c591643b1c8e2))
* **metrics:** change metric refresh time from 0.1s to 1.0s ([3b5863a](https://github.com/antoinegelloz/rf-liquidsoap/commit/3b5863a3ff2a7cfef94185175278b387cf8e7f1b))
* **multimode:** move scripts to a transcoder folder ([6601c6d](https://github.com/antoinegelloz/rf-liquidsoap/commit/6601c6de5bb3318e85e470d751b1888e34ed58e4))
* **prometheus:** add LUFS analysis for radio_prod ([627b19c](https://github.com/antoinegelloz/rf-liquidsoap/commit/627b19cc196fdeecb69ecf8fde8198e038889871))
* **prometheus:** add LUFS analysis of radio_prod ([fd8f710](https://github.com/antoinegelloz/rf-liquidsoap/commit/fd8f7106289056bec344532da7664fbf09c1ffdf))
* release v2.0.0 ([bc39945](https://github.com/antoinegelloz/rf-liquidsoap/commit/bc3994563a8dc6d7e2183b87cbce89ac3856bbb5))
* **renovate:** don't pin versions ([5ef9ce3](https://github.com/antoinegelloz/rf-liquidsoap/commit/5ef9ce34f8223dc4b841142aeafaf445fd825bb4))
* **renovate:** import common configuration elements from our main template ([14d880a](https://github.com/antoinegelloz/rf-liquidsoap/commit/14d880a6dcd16f1b1d148b7774510ff3f1261bb5))
* **scripts:** minor organisation change to support disabling outputs ([6f45715](https://github.com/antoinegelloz/rf-liquidsoap/commit/6f4571534cf9685b0340e8894ef982e11ea4454a))
* **srt:** add more srt metrics ([a8a183c](https://github.com/antoinegelloz/rf-liquidsoap/commit/a8a183c75773b2b7bea24c858e12a6e93cd596a3))
* **srt:** add srt input queue and buffer length metrics ([4ef8f51](https://github.com/antoinegelloz/rf-liquidsoap/commit/4ef8f51211453e965afedeb70a826c5cf9692e8c))
* **srt:** add srt input queue and buffer length metrics ([d430d55](https://github.com/antoinegelloz/rf-liquidsoap/commit/d430d555db85ede72a289a78666b7fe57004ee0d))
* **streamer:** add crossfade ([f8884ad](https://github.com/antoinegelloz/rf-liquidsoap/commit/f8884ad07f2ae3031ba7926e2ff02067c5466f7b))
* **streamer:** apply the replaygain tags of the files ([ee2babf](https://github.com/antoinegelloz/rf-liquidsoap/commit/ee2babf147274a8211eb50ed4bd201100e99cd94))
* **streamer:** create a srt streamer with liquidsoap ([ad4b419](https://github.com/antoinegelloz/rf-liquidsoap/commit/ad4b419d7cd96b63affc612af6bc5f3a86c350e6))
* **streamer:** force 5.1 mode for example streamer ([b846486](https://github.com/antoinegelloz/rf-liquidsoap/commit/b846486f252db64cb58b208c4b6b1cd1658959ba))
* **streamer:** support metadata and track skip with http API ([2c402c9](https://github.com/antoinegelloz/rf-liquidsoap/commit/2c402c9088e5f4aacf19b012c48ddce9958da93c))
* **streamer:** support metadata display and track skip ([a1c768a](https://github.com/antoinegelloz/rf-liquidsoap/commit/a1c768a0a46e8be5288b40073ecb78553d9e0d40))
* **surround:** use fdkaac and 256kbps for surround hifi ([98b49e0](https://github.com/antoinegelloz/rf-liquidsoap/commit/98b49e00e0ef8dd6008674a3b67fe42faae602d8))
* **testing:** improve testing tools ([394345f](https://github.com/antoinegelloz/rf-liquidsoap/commit/394345fff31f272aa58eedb7b2831c5c8e3bd9d1))
* **transcoder:** add http/icecast relay input ([15db241](https://github.com/antoinegelloz/rf-liquidsoap/commit/15db24115b36c79fb39c1af22753f0518e332f40))
* **transcoder:** add icecast input (harbor input) ([a14bdee](https://github.com/antoinegelloz/rf-liquidsoap/commit/a14bdee5084c9f8796a2b14606032188e74ba93f))
* **transcoder:** remove non-existent channel_layout setting for 5.1 ([be2646a](https://github.com/antoinegelloz/rf-liquidsoap/commit/be2646a1eb05d24d6e8b9745ca10426c8cefe360))


### Bug Fixes

* **2.2.1:** mitigate on_file_change event modification ([12fba4c](https://github.com/antoinegelloz/rf-liquidsoap/commit/12fba4c8824e54f4b04406d2a44f6bca7683316e))
* ci didnt work after moving example file to example dir ([8c44de7](https://github.com/antoinegelloz/rf-liquidsoap/commit/8c44de7fd350e0f14b9ef809c9c8a7b9c7525d52))
* **ci:** add dockerignore ([08b7344](https://github.com/antoinegelloz/rf-liquidsoap/commit/08b7344ad1f75dd33fe40c3722794c24e1fc5092))
* **ci:** ignore formatting errors in generated CHANGELOG.md file ([bd7d377](https://github.com/antoinegelloz/rf-liquidsoap/commit/bd7d377e53ac6e15cdc5681c12138a4d9203f59c))
* **ci:** parse the breaking change marker in commitlint ([2bada02](https://github.com/antoinegelloz/rf-liquidsoap/commit/2bada02f76dab6ce0f3c8a34b35f03a64df9bdea))
* **config:** update liquidsoap config to work with version 2.1.0 ([6b01802](https://github.com/antoinegelloz/rf-liquidsoap/commit/6b0180231de922d19c48d97186a86aed835db0cb))
* description cannot be blanck ([317728a](https://github.com/antoinegelloz/rf-liquidsoap/commit/317728a75ee5e41be06314bd362bca89df12ed38))
* **docker-compose:** fix ports and descriptions for example containers ([77211f6](https://github.com/antoinegelloz/rf-liquidsoap/commit/77211f647ad9c37c6ce9aa796ad00b22ede8b3f9))
* **examples:** change mystreamersurround ports (dupe with mystreamer) ([8c97cb1](https://github.com/antoinegelloz/rf-liquidsoap/commit/8c97cb146ffc8279bcbe63c92472bc9d37946659))
* **formats:** use real codec names for aac formats, files and fix profiles ([cf3f362](https://github.com/antoinegelloz/rf-liquidsoap/commit/cf3f362479a6b7e2a95b0b1efe10647f766362d1))
* **formats:** use real codec names for aac formats, files and fix profiles ([73e1b11](https://github.com/antoinegelloz/rf-liquidsoap/commit/73e1b11243b049a0b61734dd0b8c8462be03ca67))
* **gitlab:** add new test dir ([394345f](https://github.com/antoinegelloz/rf-liquidsoap/commit/394345fff31f272aa58eedb7b2831c5c8e3bd9d1))
* **gitlabci:** indent gitlab-ci according to our norm ([06c32bd](https://github.com/antoinegelloz/rf-liquidsoap/commit/06c32bddbe16fab3b9c43434a3d5474741d92b2b))
* **hls:** by default, use local hls storage ([394345f](https://github.com/antoinegelloz/rf-liquidsoap/commit/394345fff31f272aa58eedb7b2831c5c8e3bd9d1))
* **hls:** cast segment duration to int and bump liquidsoap ([7365a5f](https://github.com/antoinegelloz/rf-liquidsoap/commit/7365a5f3a6adce7e9aad355d4f0d51207ed8b827))
* **hls:** set correct permissions to hls segments output folder ([03e2322](https://github.com/antoinegelloz/rf-liquidsoap/commit/03e23227443fddab8dc533463ebdf82125c6a930))
* **http:** invert conditions for http commands ([35ac1c9](https://github.com/antoinegelloz/rf-liquidsoap/commit/35ac1c9450ac27448626a4a3540932b21be1c21b))
* **http:** rename json outputs to match initial formating ([36d6909](https://github.com/antoinegelloz/rf-liquidsoap/commit/36d6909f4ffc9a484c194e9cce76eabc50940f4a))
* **icecast:** add a clock with the buffer ([120038f](https://github.com/antoinegelloz/rf-liquidsoap/commit/120038fe351c378969a39d1b46e51beb72bc14fa))
* **icecast:** add missing quote ([c1fe528](https://github.com/antoinegelloz/rf-liquidsoap/commit/c1fe5282249593fa52dd494148e2fad4acd63c66))
* **logs:** make hls logs a single line ([77871a8](https://github.com/antoinegelloz/rf-liquidsoap/commit/77871a8a009930778b4806e8333a937bc028df89))
* **Makefile:** repair make artifact so it always works ([f0e9d09](https://github.com/antoinegelloz/rf-liquidsoap/commit/f0e9d09b14b1e20242ef87d75464b1db30c30f7e))
* **metadata:** include radio name in ids ([452d222](https://github.com/antoinegelloz/rf-liquidsoap/commit/452d22264fcd8ade224f81345bab07434ebbeb5a))
* **metrics:** repair srt metrics so they really refresh each second ([ce5ec0d](https://github.com/antoinegelloz/rf-liquidsoap/commit/ce5ec0d1b2360f4aaf99bcde82c2bfff42036116))
* **prometheus:** fix prometheus config and change metrics ports ([7716413](https://github.com/antoinegelloz/rf-liquidsoap/commit/77164134a9f791cc4a9bfefb851cb7e72cfc2327))
* **qualities:** increase bitrate for insane AAC_LC 5.1 profile ([f48e9e9](https://github.com/antoinegelloz/rf-liquidsoap/commit/f48e9e9752d017cd4cc3eefd63b8457962b24df7))
* **queues:** increase again the generic queues number ([1849472](https://github.com/antoinegelloz/rf-liquidsoap/commit/1849472e078be1d3c21539df85cd59dde10080e5))
* **readme:** remove https from URLs ([2663fd9](https://github.com/antoinegelloz/rf-liquidsoap/commit/2663fd98776769107f4e34bde5d76e3d9c39f651))
* remove a typo in the Makefile ([ea0e686](https://github.com/antoinegelloz/rf-liquidsoap/commit/ea0e6863b090c175a736fac6796d6292e13587e1))
* remove undefined milestones ([53a11dc](https://github.com/antoinegelloz/rf-liquidsoap/commit/53a11dc8cb651e6f965317ede3c10bd247b1b3dc))
* **renovate:** change semantic commit type ([0e63014](https://github.com/antoinegelloz/rf-liquidsoap/commit/0e63014c7f1aaaed55d1fcd99c068a6849d95c62))
* **renovate:** disable digests on everything but liquidsoap ([1f9eec3](https://github.com/antoinegelloz/rf-liquidsoap/commit/1f9eec34ac8ecac300768825891846bc1653d1ac))
* **settings:** keep one fast queue to protect clocked threads ([#49](https://github.com/antoinegelloz/rf-liquidsoap/issues/49)) ([0ba424f](https://github.com/antoinegelloz/rf-liquidsoap/commit/0ba424faa980d7575937ab08afbc846458c641ff))
* **sources:** don't define source type when using sources like safe_blank ([dae3d5c](https://github.com/antoinegelloz/rf-liquidsoap/commit/dae3d5c7a7e7fe419496e9ec507e12e89d8f760c))
* **srt:** disable stats on srt input ([6e414c4](https://github.com/antoinegelloz/rf-liquidsoap/commit/6e414c48381e9c592dcaf7ad36392035a51e5d74))
* **srt:** disable stats on srt input ([c41899f](https://github.com/antoinegelloz/rf-liquidsoap/commit/c41899fe0ddfd256c5a2cac8968da51de2f7e978))
* **srt:** remove clock_safe in srt inputs ([afe0c34](https://github.com/antoinegelloz/rf-liquidsoap/commit/afe0c34de60887f499c6eed3a48032b6983acf1a))
* **streamer:** read the playlist as m3u ([28794c1](https://github.com/antoinegelloz/rf-liquidsoap/commit/28794c11e13bd8c0a6479f6eb75be951049624f3))
* **surround:** make mystreamersurround 6-channel output ([9e721a1](https://github.com/antoinegelloz/rf-liquidsoap/commit/9e721a1beb452465d0715aa03e803f4677e6a526))
* **syntax:** transform !x to new syntax x() ([469e419](https://github.com/antoinegelloz/rf-liquidsoap/commit/469e41919809a2035c3d58568a8251bf4ab0a5da))
* **transcoder:** set the default channels from the radio config ([6cfb9d6](https://github.com/antoinegelloz/rf-liquidsoap/commit/6cfb9d67549894ff2fee0c40b42eaf395d5c507c))
* use liquidsoap-prettier v1.8.3 to format files ([f753e28](https://github.com/antoinegelloz/rf-liquidsoap/commit/f753e281bdb25bcae8b23716946e032b3b86f355))
* use liquidsoap-prettier v1.8.3 to format files ([a88556c](https://github.com/antoinegelloz/rf-liquidsoap/commit/a88556ce775d978fc40305c332924a54bd8fb533))
* vary hostname by env in 50-hls.liq ([93089b0](https://github.com/antoinegelloz/rf-liquidsoap/commit/93089b063ce69e6a199780227b234a686432a55a))

## [2.13.0](https://github.com/radiofrance/rf-liquidsoap/compare/v2.12.0...v2.13.0) (2026-10-22)


### Features

* **ci:** add sha256 checksum in each release ([28b4c16](https://github.com/radiofrance/rf-liquidsoap/commit/28b4c165cf977529cf4b98f0ae0d2dc1aec461d1))

## [2.12.0](https://github.com/radiofrance/rf-liquidsoap/compare/v2.11.0...v2.12.0) (2026-10-22)


### Features

* **renovate:** import common configuration elements from our main template ([14d880a](https://github.com/radiofrance/rf-liquidsoap/commit/14d880a6dcd16f1b1d148b7774510ff3f1261bb5))
* **transcoder:** add http/icecast relay input ([15db241](https://github.com/radiofrance/rf-liquidsoap/commit/15db24115b36c79fb39c1af22753f0518e332f40))
* **transcoder:** add icecast input (harbor input) ([a14bdee](https://github.com/radiofrance/rf-liquidsoap/commit/a14bdee5084c9f8796a2b14606032188e74ba93f))

## [2.11.0](https://github.com/radiofrance/rf-liquidsoap/compare/v2.10.0...v2.11.0) (2026-10-12)


### Features

* **CI:** add new commitlint job ([e34c8a4](https://github.com/radiofrance/rf-liquidsoap/commit/e34c8a44aedeeb29c45d2d062ea276307aa3032d))
* **CI:** add new commitlint job ([7a9e795](https://github.com/radiofrance/rf-liquidsoap/commit/7a9e795b3ed2692ec66355a8368cbf83be7e81cf))
* **CI:** add PR pre-release artifacts ([dd5ac6b](https://github.com/radiofrance/rf-liquidsoap/commit/dd5ac6b6b75dd3c330340d970c03d0da742dc1b8))
* **CI:** add PR pre-release artifacts ([abc88a4](https://github.com/radiofrance/rf-liquidsoap/commit/abc88a47dc3426d571ac50bb453c3d33e51efc76))
* **CI:** add yamllint ([f333753](https://github.com/radiofrance/rf-liquidsoap/commit/f33375393668cddc1e8f9c5c1bb87d344524bd49))
* **CI:** add yamllint ([a45b51f](https://github.com/radiofrance/rf-liquidsoap/commit/a45b51fc724dc4974a418aa882cd2c6f1d75711d))
* **CI:** improve the release workflow ([951266f](https://github.com/radiofrance/rf-liquidsoap/commit/951266f68eed21074957be7ce82ef25c1fa34a11))
* **ci:** use npm ci instead of manual dependencies management in github action ([ce3506f](https://github.com/radiofrance/rf-liquidsoap/commit/ce3506f18dbd3b79fdeafd065ebb223fd694196c))
* **ci:** use npm commands to run validation scripts in github action ([ed9ed01](https://github.com/radiofrance/rf-liquidsoap/commit/ed9ed0183380f6fa70cb7fc605351ebb76aff8d7))


### Bug Fixes

* **ci:** ignore formatting errors in generated CHANGELOG.md file ([bd7d377](https://github.com/radiofrance/rf-liquidsoap/commit/bd7d377e53ac6e15cdc5681c12138a4d9203f59c))
* **surround:** make mystreamersurround 6-channel output ([9e721a1](https://github.com/radiofrance/rf-liquidsoap/commit/9e721a1beb452465d0715aa03e803f4677e6a526))
* use liquidsoap-prettier v1.8.3 to format files ([f753e28](https://github.com/radiofrance/rf-liquidsoap/commit/f753e281bdb25bcae8b23716946e032b3b86f355))
* use liquidsoap-prettier v1.8.3 to format files ([a88556c](https://github.com/radiofrance/rf-liquidsoap/commit/a88556ce775d978fc40305c332924a54bd8fb533))

### [2.10.0](https://www.github.com/radiofrance/rf-liquidsoap/compare/v2.0.9...v2.10.0) (2026-02-17)

- chore(deps): update actions/checkout action to v5
- test: add commitlintrc
- feat(transcoder): remove non-existent channel_layout setting for 5.1
- chore(liquidsoap): bump liquidsoap version to stable v2.4.2
- feat(Makefile): add liquidsoap-prettier in makefile

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
