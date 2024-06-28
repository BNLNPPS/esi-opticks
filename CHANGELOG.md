# [1.0.0-betatest.4](https://github.com/BNLNPPS/esi-shell/compare/1.0.0-betatest.3...1.0.0-betatest.4) (2024-06-28)


### Bug Fixes

* 3 ([a8919a7](https://github.com/BNLNPPS/esi-shell/commit/a8919a717f47eb50f1f8857ec6148052a75da144))





test version 1.0.0-betatest.4

# [1.0.0-betatest.3](https://github.com/BNLNPPS/esi-shell/compare/1.0.0-betatest.2...1.0.0-betatest.3) (2024-06-28)


### Bug Fixes

* 2 ([6318398](https://github.com/BNLNPPS/esi-shell/commit/63183981468257ea9461f01824c8fe38bd9ea421))





test version 1.0.0-betatest.3

# [1.0.0-betatest.2](https://github.com/BNLNPPS/esi-shell/compare/1.0.0-betatest.1...1.0.0-betatest.2) (2024-06-28)


### Bug Fixes

* do not install npm ([1202d4d](https://github.com/BNLNPPS/esi-shell/commit/1202d4d44f39e7a37f1685e63f9eeda34e1b4b52))
* try 1 ([c4d6bd3](https://github.com/BNLNPPS/esi-shell/commit/c4d6bd3333fee7025c55b77c34ea5d9254d9bfd6))





test version 1.0.0-betatest.2

# 1.0.0-betatest.1 (2024-06-28)


### Bug Fixes

* always pull updated image from registry ([#62](https://github.com/BNLNPPS/esi-shell/issues/62)) ([33f5b06](https://github.com/BNLNPPS/esi-shell/commit/33f5b0614ecd4ce3918492c22a087aa395767932))
* **build:** compile for generic x86_64 (v3) microarchitecture ([#90](https://github.com/BNLNPPS/esi-shell/issues/90)) ([6a4a045](https://github.com/BNLNPPS/esi-shell/commit/6a4a045a530136c877a9bf7966b3878b1478a01a))
* **build:** keep build cache dir ([#21](https://github.com/BNLNPPS/esi-shell/issues/21)) ([d81672d](https://github.com/BNLNPPS/esi-shell/commit/d81672d8f4a08532e2719851320ee9e3112cb5a5))
* **eic-shell:** switch to ghcr.io registry ([928acba](https://github.com/BNLNPPS/esi-shell/commit/928acba495e3865e5d986e899de8993abcd63768))
* **env:** activate virtual environment via poetry ([5413d8b](https://github.com/BNLNPPS/esi-shell/commit/5413d8b2949664690b32e91556b5a0da7cd0b9b8))
* **env:** define environment variable TMP expected by opticks tests ([#85](https://github.com/BNLNPPS/esi-shell/issues/85)) ([06780ab](https://github.com/BNLNPPS/esi-shell/commit/06780ab745b8a0d931910d203bff185ca4a230b7))
* **env:** keep g4emlow ([a3761be](https://github.com/BNLNPPS/esi-shell/commit/a3761be84a2277ad610ea58b92b85aff906d58a2))
* **env:** load xerces-c, update PATH ([#66](https://github.com/BNLNPPS/esi-shell/issues/66)) ([044e0ba](https://github.com/BNLNPPS/esi-shell/commit/044e0ba7bff3e4c3e4d3465376341cd7fcddddde))
* **esi-shell:** avoid building code (OptiX) on shell startup ([#23](https://github.com/BNLNPPS/esi-shell/issues/23)) ([76320cf](https://github.com/BNLNPPS/esi-shell/commit/76320cf6e8d43e37414d0469ae8f81c950f97231))
* **esi-shell:** avoid passing options to echo ([e009ef9](https://github.com/BNLNPPS/esi-shell/commit/e009ef9fa085e1590d8f41714fbb05ac152796b7))
* **esi-shell:** drop support for singularity with GPU (for now) ([#22](https://github.com/BNLNPPS/esi-shell/issues/22)) ([4cb9d19](https://github.com/BNLNPPS/esi-shell/commit/4cb9d19c3180ac66aab8d58a4e615cd4e0e6567e))
* **esi-shell:** improve user experience ([#20](https://github.com/BNLNPPS/esi-shell/issues/20)) ([0a464af](https://github.com/BNLNPPS/esi-shell/commit/0a464af1dd9d01cedb98dd50b3f3681dbe73da22))
* **esi-shell:** run commands without TTY ([71d09ae](https://github.com/BNLNPPS/esi-shell/commit/71d09aead72b7ee821f02842c8906d126dbfbe88))
* **esi-shell:** support only linux ([#13](https://github.com/BNLNPPS/esi-shell/issues/13)) ([6cfb154](https://github.com/BNLNPPS/esi-shell/commit/6cfb154d82fe252089b10ef92db3a63707c2a60b))
* install cmake directly ([#88](https://github.com/BNLNPPS/esi-shell/issues/88)) ([e264829](https://github.com/BNLNPPS/esi-shell/commit/e264829a56638035fd0c51479fbfcd65d251a3f6)), closes [#87](https://github.com/BNLNPPS/esi-shell/issues/87)
* install npm + plugin ([b03e512](https://github.com/BNLNPPS/esi-shell/commit/b03e5127ff4080c142e7c82034b239bdd8e190bb))
* patch spack default modules.yaml ([#27](https://github.com/BNLNPPS/esi-shell/issues/27)) ([23183af](https://github.com/BNLNPPS/esi-shell/commit/23183af24648db3fdcdf0c5a9dc94385d9aa1b9c))
* remove container after tests ([105a4ba](https://github.com/BNLNPPS/esi-shell/commit/105a4ba3d2de5db92c96e451a40e5fcc50a96a4d))
* remove docker commands ([ca04587](https://github.com/BNLNPPS/esi-shell/commit/ca04587b77729624b343736af9747ca7b844e125))
* set compute capability to 5.2 compatible with Quadro M4000 ([#1](https://github.com/BNLNPPS/esi-shell/issues/1)) ([b1d7513](https://github.com/BNLNPPS/esi-shell/commit/b1d751357c61ac3e18a94262536ca397d1fa54e7))
* **shell:** enable optix with driver capabilities ([#69](https://github.com/BNLNPPS/esi-shell/issues/69)) ([6b4ea3f](https://github.com/BNLNPPS/esi-shell/commit/6b4ea3fa1142928c5762904cf68b325e30abbde6)), closes [#68](https://github.com/BNLNPPS/esi-shell/issues/68)
* simplify build workflow, leverage login scripts ([#8](https://github.com/BNLNPPS/esi-shell/issues/8)) ([fd974b4](https://github.com/BNLNPPS/esi-shell/commit/fd974b4c42dbcb8c1247cd262bafbf16e4eb071b))
* use correct gdml file ([c014536](https://github.com/BNLNPPS/esi-shell/commit/c014536e4452a815bef61a2b03bfe456a898bb7d))
* use default HOME and PWD inside container ([#80](https://github.com/BNLNPPS/esi-shell/issues/80)) ([1bf8b2e](https://github.com/BNLNPPS/esi-shell/commit/1bf8b2e731c29011cfe315a63706c6efe440edaa))
* use single command to execute container commands ([5a0f897](https://github.com/BNLNPPS/esi-shell/commit/5a0f89767baf28fe106dc365b07ed5300283bd12))
* version reference ([ffd86fb](https://github.com/BNLNPPS/esi-shell/commit/ffd86fb5066631fbabe1982b7c8058f7f235a0e1))


### Features

* add esi-shell ([#6](https://github.com/BNLNPPS/esi-shell/issues/6)) ([fa859aa](https://github.com/BNLNPPS/esi-shell/commit/fa859aa91496b27fb66d891ef78a28ec90b45c50))
* build gpu code dependent on OptiX, run opticks tests ([#49](https://github.com/BNLNPPS/esi-shell/issues/49)) ([#53](https://github.com/BNLNPPS/esi-shell/issues/53)) ([5f58b7b](https://github.com/BNLNPPS/esi-shell/commit/5f58b7be7d1893ba7247de5b95f43a7349aa4cf8)), closes [#50](https://github.com/BNLNPPS/esi-shell/issues/50)
* **esi-shell:** exec user command, pass through container options ([1217f36](https://github.com/BNLNPPS/esi-shell/commit/1217f362f3b05e78146bbda07537126815801e75))
* setup semantic release ([ca0553c](https://github.com/BNLNPPS/esi-shell/commit/ca0553c24acb7da072314c1b4f31bc3a84d79460))
* update opticks ([#42](https://github.com/BNLNPPS/esi-shell/issues/42)) ([4338f7c](https://github.com/BNLNPPS/esi-shell/commit/4338f7c51bb92b643bfbef9cb32920d517f26395)), closes [#41](https://github.com/BNLNPPS/esi-shell/issues/41)
* upgrade opticks ([#39](https://github.com/BNLNPPS/esi-shell/issues/39)) ([2d6706a](https://github.com/BNLNPPS/esi-shell/commit/2d6706a0ccf8bb79b55a538c1437464ab5462648))
* upgrade opticks to main@b55f15bd ([#26](https://github.com/BNLNPPS/esi-shell/issues/26)) ([946da36](https://github.com/BNLNPPS/esi-shell/commit/946da36cdc7fe309c63a8547ca8aeeeb0551a313))


### Reverts

* Revert "feat: build gpu code dependent on OptiX, run opticks tests (#49)" ([a301bd2](https://github.com/BNLNPPS/esi-shell/commit/a301bd290c43476ef5fa674ce7cc52f326fa29e9)), closes [#49](https://github.com/BNLNPPS/esi-shell/issues/49)
* restore removed pull of latest image for cache purposes ([#47](https://github.com/BNLNPPS/esi-shell/issues/47)) ([8138919](https://github.com/BNLNPPS/esi-shell/commit/8138919d14d20646535e0c80c1e1266c04e9543b))





test version 1.0.0-betatest.1

# [1.0.0-beta.15](https://github.com/BNLNPPS/esi-shell/compare/1.0.0-beta.14...1.0.0-beta.15) (2024-06-20)


### Bug Fixes

* **build:** compile for generic x86_64 (v3) microarchitecture ([#90](https://github.com/BNLNPPS/esi-shell/issues/90)) ([6a4a045](https://github.com/BNLNPPS/esi-shell/commit/6a4a045a530136c877a9bf7966b3878b1478a01a))

# [1.0.0-beta.14](https://github.com/BNLNPPS/esi-shell/compare/1.0.0-beta.13...1.0.0-beta.14) (2024-06-19)


### Bug Fixes

* install cmake directly ([#88](https://github.com/BNLNPPS/esi-shell/issues/88)) ([e264829](https://github.com/BNLNPPS/esi-shell/commit/e264829a56638035fd0c51479fbfcd65d251a3f6)), closes [#87](https://github.com/BNLNPPS/esi-shell/issues/87)

# [1.0.0-beta.13](https://github.com/BNLNPPS/esi-shell/compare/1.0.0-beta.12...1.0.0-beta.13) (2024-06-07)


### Bug Fixes

* **env:** define environment variable TMP expected by opticks tests ([#85](https://github.com/BNLNPPS/esi-shell/issues/85)) ([06780ab](https://github.com/BNLNPPS/esi-shell/commit/06780ab745b8a0d931910d203bff185ca4a230b7))

# [1.0.0-beta.12](https://github.com/BNLNPPS/esi-shell/compare/1.0.0-beta.11...1.0.0-beta.12) (2024-06-03)


### Bug Fixes

* **esi-shell:** avoid passing options to echo ([e009ef9](https://github.com/BNLNPPS/esi-shell/commit/e009ef9fa085e1590d8f41714fbb05ac152796b7))

# [1.0.0-beta.11](https://github.com/BNLNPPS/esi-shell/compare/1.0.0-beta.10...1.0.0-beta.11) (2024-05-31)


### Bug Fixes

* **env:** activate virtual environment via poetry ([5413d8b](https://github.com/BNLNPPS/esi-shell/commit/5413d8b2949664690b32e91556b5a0da7cd0b9b8))
* **esi-shell:** run commands without TTY ([71d09ae](https://github.com/BNLNPPS/esi-shell/commit/71d09aead72b7ee821f02842c8906d126dbfbe88))
* use default HOME and PWD inside container ([#80](https://github.com/BNLNPPS/esi-shell/issues/80)) ([1bf8b2e](https://github.com/BNLNPPS/esi-shell/commit/1bf8b2e731c29011cfe315a63706c6efe440edaa))
* use single command to execute container commands ([5a0f897](https://github.com/BNLNPPS/esi-shell/commit/5a0f89767baf28fe106dc365b07ed5300283bd12))


### Features

* **esi-shell:** exec user command, pass through container options ([1217f36](https://github.com/BNLNPPS/esi-shell/commit/1217f362f3b05e78146bbda07537126815801e75))

# [1.0.0-beta.10](https://github.com/BNLNPPS/esi-shell/compare/1.0.0-beta.9...1.0.0-beta.10) (2024-05-14)


### Bug Fixes

* **env:** keep g4emlow ([a3761be](https://github.com/BNLNPPS/esi-shell/commit/a3761be84a2277ad610ea58b92b85aff906d58a2))

# [1.0.0-beta.9](https://github.com/BNLNPPS/esi-shell/compare/1.0.0-beta.8...1.0.0-beta.9) (2024-05-14)


### Bug Fixes

* **shell:** enable optix with driver capabilities ([#69](https://github.com/BNLNPPS/esi-shell/issues/69)) ([6b4ea3f](https://github.com/BNLNPPS/esi-shell/commit/6b4ea3fa1142928c5762904cf68b325e30abbde6)), closes [#68](https://github.com/BNLNPPS/esi-shell/issues/68)

# [1.0.0-beta.8](https://github.com/BNLNPPS/esi-shell/compare/1.0.0-beta.7...1.0.0-beta.8) (2024-05-13)


### Bug Fixes

* **env:** load xerces-c, update PATH ([#66](https://github.com/BNLNPPS/esi-shell/issues/66)) ([044e0ba](https://github.com/BNLNPPS/esi-shell/commit/044e0ba7bff3e4c3e4d3465376341cd7fcddddde))

# [1.0.0-beta.7](https://github.com/BNLNPPS/esi-shell/compare/1.0.0-beta.6...1.0.0-beta.7) (2024-05-10)


### Bug Fixes

* always pull updated image from registry ([#62](https://github.com/BNLNPPS/esi-shell/issues/62)) ([33f5b06](https://github.com/BNLNPPS/esi-shell/commit/33f5b0614ecd4ce3918492c22a087aa395767932))

# [1.0.0-beta.6](https://github.com/BNLNPPS/esi-shell/compare/1.0.0-beta.5...1.0.0-beta.6) (2024-05-07)


### Features

* build gpu code dependent on OptiX, run opticks tests ([#49](https://github.com/BNLNPPS/esi-shell/issues/49)) ([#53](https://github.com/BNLNPPS/esi-shell/issues/53)) ([5f58b7b](https://github.com/BNLNPPS/esi-shell/commit/5f58b7be7d1893ba7247de5b95f43a7349aa4cf8)), closes [#50](https://github.com/BNLNPPS/esi-shell/issues/50)

# [1.0.0-beta.5](https://github.com/BNLNPPS/esi-shell/compare/1.0.0-beta.4...1.0.0-beta.5) (2024-05-07)


### Reverts

* Revert "feat: build gpu code dependent on OptiX, run opticks tests (#49)" ([a301bd2](https://github.com/BNLNPPS/esi-shell/commit/a301bd290c43476ef5fa674ce7cc52f326fa29e9)), closes [#49](https://github.com/BNLNPPS/esi-shell/issues/49)

# [1.0.0-beta.4](https://github.com/BNLNPPS/esi-shell/compare/1.0.0-beta.3...1.0.0-beta.4) (2024-05-06)


### Features

* update opticks ([#42](https://github.com/BNLNPPS/esi-shell/issues/42)) ([4338f7c](https://github.com/BNLNPPS/esi-shell/commit/4338f7c51bb92b643bfbef9cb32920d517f26395)), closes [#41](https://github.com/BNLNPPS/esi-shell/issues/41)


### Reverts

* restore removed pull of latest image for cache purposes ([#47](https://github.com/BNLNPPS/esi-shell/issues/47)) ([8138919](https://github.com/BNLNPPS/esi-shell/commit/8138919d14d20646535e0c80c1e1266c04e9543b))

# [1.0.0-beta.3](https://github.com/BNLNPPS/esi-opticks/compare/1.0.0-beta.2...1.0.0-beta.3) (2024-05-03)


### Features

* upgrade opticks ([#39](https://github.com/BNLNPPS/esi-opticks/issues/39)) ([2d6706a](https://github.com/BNLNPPS/esi-opticks/commit/2d6706a0ccf8bb79b55a538c1437464ab5462648))

# [1.0.0-beta.2](https://github.com/BNLNPPS/esi-opticks/compare/1.0.0-beta.1...1.0.0-beta.2) (2024-04-26)


### Bug Fixes

* **eic-shell:** switch to ghcr.io registry ([928acba](https://github.com/BNLNPPS/esi-opticks/commit/928acba495e3865e5d986e899de8993abcd63768))
* remove container after tests ([105a4ba](https://github.com/BNLNPPS/esi-opticks/commit/105a4ba3d2de5db92c96e451a40e5fcc50a96a4d))

# 1.0.0-beta.1 (2024-04-26)


### Bug Fixes

* **build:** keep build cache dir ([#21](https://github.com/BNLNPPS/esi-opticks/issues/21)) ([d81672d](https://github.com/BNLNPPS/esi-opticks/commit/d81672d8f4a08532e2719851320ee9e3112cb5a5))
* **esi-shell:** avoid building code (OptiX) on shell startup ([#23](https://github.com/BNLNPPS/esi-opticks/issues/23)) ([76320cf](https://github.com/BNLNPPS/esi-opticks/commit/76320cf6e8d43e37414d0469ae8f81c950f97231))
* **esi-shell:** drop support for singularity with GPU (for now) ([#22](https://github.com/BNLNPPS/esi-opticks/issues/22)) ([4cb9d19](https://github.com/BNLNPPS/esi-opticks/commit/4cb9d19c3180ac66aab8d58a4e615cd4e0e6567e))
* **esi-shell:** improve user experience ([#20](https://github.com/BNLNPPS/esi-opticks/issues/20)) ([0a464af](https://github.com/BNLNPPS/esi-opticks/commit/0a464af1dd9d01cedb98dd50b3f3681dbe73da22))
* **esi-shell:** support only linux ([#13](https://github.com/BNLNPPS/esi-opticks/issues/13)) ([6cfb154](https://github.com/BNLNPPS/esi-opticks/commit/6cfb154d82fe252089b10ef92db3a63707c2a60b))
* patch spack default modules.yaml ([#27](https://github.com/BNLNPPS/esi-opticks/issues/27)) ([23183af](https://github.com/BNLNPPS/esi-opticks/commit/23183af24648db3fdcdf0c5a9dc94385d9aa1b9c))
* set compute capability to 5.2 compatible with Quadro M4000 ([#1](https://github.com/BNLNPPS/esi-opticks/issues/1)) ([b1d7513](https://github.com/BNLNPPS/esi-opticks/commit/b1d751357c61ac3e18a94262536ca397d1fa54e7))
* simplify build workflow, leverage login scripts ([#8](https://github.com/BNLNPPS/esi-opticks/issues/8)) ([fd974b4](https://github.com/BNLNPPS/esi-opticks/commit/fd974b4c42dbcb8c1247cd262bafbf16e4eb071b))
* use correct gdml file ([c014536](https://github.com/BNLNPPS/esi-opticks/commit/c014536e4452a815bef61a2b03bfe456a898bb7d))


### Features

* add esi-shell ([#6](https://github.com/BNLNPPS/esi-opticks/issues/6)) ([fa859aa](https://github.com/BNLNPPS/esi-opticks/commit/fa859aa91496b27fb66d891ef78a28ec90b45c50))
* setup semantic release ([ca0553c](https://github.com/BNLNPPS/esi-opticks/commit/ca0553c24acb7da072314c1b4f31bc3a84d79460))
* upgrade opticks to main@b55f15bd ([#26](https://github.com/BNLNPPS/esi-opticks/issues/26)) ([946da36](https://github.com/BNLNPPS/esi-opticks/commit/946da36cdc7fe309c63a8547ca8aeeeb0551a313))
