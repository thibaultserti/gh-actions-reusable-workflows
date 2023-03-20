# [1.6.0](https://github.com/thibaultserti/gh-actions-reusable-workflows/compare/v1.5.6...v1.6.0) (2023-03-20)


### Features

* **go:** add codeclimate, codecov and codeQL ([0e3c1ce](https://github.com/thibaultserti/gh-actions-reusable-workflows/commit/0e3c1ce5f49cbc0abf275c9923ee76a4e4f4297a)), closes [#1](https://github.com/thibaultserti/gh-actions-reusable-workflows/issues/1) [#2](https://github.com/thibaultserti/gh-actions-reusable-workflows/issues/2) [#3](https://github.com/thibaultserti/gh-actions-reusable-workflows/issues/3)
* **python:** add codeclimate, codecov and codeQL ([ef5953f](https://github.com/thibaultserti/gh-actions-reusable-workflows/commit/ef5953fbe4accce193ba1d0539232a2d4af5a992)), closes [#1](https://github.com/thibaultserti/gh-actions-reusable-workflows/issues/1) [#2](https://github.com/thibaultserti/gh-actions-reusable-workflows/issues/2) [#3](https://github.com/thibaultserti/gh-actions-reusable-workflows/issues/3)

## [1.5.6](https://github.com/thibaultserti/gh-actions-reusable-workflows/compare/v1.5.5...v1.5.6) (2023-03-19)


### Bug Fixes

* fix signed image digest ([6cd59d5](https://github.com/thibaultserti/gh-actions-reusable-workflows/commit/6cd59d50b95298251cdc03d586b7d80909e8da97))

## [1.5.5](https://github.com/thibaultserti/gh-actions-reusable-workflows/compare/v1.5.4...v1.5.5) (2023-03-18)


### Bug Fixes

* remove v in docker tagging ([3dd58d1](https://github.com/thibaultserti/gh-actions-reusable-workflows/commit/3dd58d19822d5ef936074b1281c20a4b81923b23))

## [1.5.4](https://github.com/thibaultserti/gh-actions-reusable-workflows/compare/v1.5.3...v1.5.4) (2023-03-18)


### Bug Fixes

* fix typo ([63e7e9a](https://github.com/thibaultserti/gh-actions-reusable-workflows/commit/63e7e9ad65147263b2c6696efe44ec3e726366cf))

## [1.5.3](https://github.com/thibaultserti/gh-actions-reusable-workflows/compare/v1.5.2...v1.5.3) (2023-03-18)


### Bug Fixes

* fix needless check-secrets ([0cb24a9](https://github.com/thibaultserti/gh-actions-reusable-workflows/commit/0cb24a93e76c0ff890bfe80e15ed5b8e1e2045c9))

## [1.5.2](https://github.com/thibaultserti/gh-actions-reusable-workflows/compare/v1.5.1...v1.5.2) (2023-03-18)


### Bug Fixes

* use sigstore with OIDC signing ([1fa18e3](https://github.com/thibaultserti/gh-actions-reusable-workflows/commit/1fa18e3e4ecd5402567519062e184e709d8b61c2))

## [1.5.1](https://github.com/thibaultserti/gh-actions-reusable-workflows/compare/v1.5.0...v1.5.1) (2023-03-18)


### Bug Fixes

* fix inherits secrets in check-secrets ([3ab1457](https://github.com/thibaultserti/gh-actions-reusable-workflows/commit/3ab14576093ec8f0d9fcb81a8002f9e70dd37e49))

# [1.5.0](https://github.com/thibaultserti/gh-actions-reusable-workflows/compare/v1.4.0...v1.5.0) (2023-03-18)


### Bug Fixes

* add emojis where it was forgotten ([bfdef2d](https://github.com/thibaultserti/gh-actions-reusable-workflows/commit/bfdef2dc79eccdfad2e08d565021094689dfbe62))
* fix forgotten needs for check-variables and check-secrets ([cb913b4](https://github.com/thibaultserti/gh-actions-reusable-workflows/commit/cb913b4e1a447ec99b004ff570e031a482169a51))


### Features

* add check Github secrets workflow ([0ab1b09](https://github.com/thibaultserti/gh-actions-reusable-workflows/commit/0ab1b0961fc8f5d02a0138524bd90d209b1cd030))
* add cosign workflow ([56d8121](https://github.com/thibaultserti/gh-actions-reusable-workflows/commit/56d8121d94a0101a748616ee6bdd7d433574e9bd)), closes [#7](https://github.com/thibaultserti/gh-actions-reusable-workflows/issues/7)
* add emoji for each steps ([46198e8](https://github.com/thibaultserti/gh-actions-reusable-workflows/commit/46198e8b60fd5351f0ed120432f6683a59fedd5f)), closes [#9](https://github.com/thibaultserti/gh-actions-reusable-workflows/issues/9)
* **docker-build:** add hadolint ([c94bbab](https://github.com/thibaultserti/gh-actions-reusable-workflows/commit/c94bbabb4eacfe2afccc54aa5a9c416ea777822d)), closes [#8](https://github.com/thibaultserti/gh-actions-reusable-workflows/issues/8)

# [1.4.0](https://github.com/thibaultserti/gh-actions-reusable-workflows/compare/v1.3.1...v1.4.0) (2023-03-18)


### Features

* add check Github variables workflow ([4579088](https://github.com/thibaultserti/gh-actions-reusable-workflows/commit/4579088163d2fc96d69496afaedd427e6c030e68)), closes [#11](https://github.com/thibaultserti/gh-actions-reusable-workflows/issues/11)

## [1.3.1](https://github.com/thibaultserti/gh-actions-reusable-workflows/compare/v1.3.0...v1.3.1) (2023-03-15)


### Bug Fixes

* remove platforms support in docker build test ([46d7f0d](https://github.com/thibaultserti/gh-actions-reusable-workflows/commit/46d7f0d123bd182de751754b3138b5ebc7e411c5))

# [1.3.0](https://github.com/thibaultserti/gh-actions-reusable-workflows/compare/v1.2.0...v1.3.0) (2023-03-15)


### Features

* add platforms to docker build inputs ([568c5fc](https://github.com/thibaultserti/gh-actions-reusable-workflows/commit/568c5fc2c85c072872fed7adc2c73ae561829ddd))

# [1.2.0](https://github.com/thibaultserti/gh-actions-reusable-workflows/compare/v1.1.1...v1.2.0) (2023-03-15)


### Features

* add plugins exec to python sem release ([36e14da](https://github.com/thibaultserti/gh-actions-reusable-workflows/commit/36e14dac08c9dcabc55c83d18642a3f7e8c5831b))

## [1.1.1](https://github.com/thibaultserti/gh-actions-reusable-workflows/compare/v1.1.0...v1.1.1) (2023-03-15)


### Bug Fixes

* fix typo ([30be205](https://github.com/thibaultserti/gh-actions-reusable-workflows/commit/30be205c901f401e80b3e901e3b98f2611b7535f))

# [1.1.0](https://github.com/thibaultserti/gh-actions-reusable-workflows/compare/v1.0.0...v1.1.0) (2023-03-15)


### Features

* add python reusable workflows ([95220aa](https://github.com/thibaultserti/gh-actions-reusable-workflows/commit/95220aad44f3ba854812f0f17a23af5ba81a1c0b))

# 1.0.0 (2023-03-12)


### Features

* add golang reusable workflows ([702efd5](https://github.com/thibaultserti/gh-actions-reusable-workflows/commit/702efd57053f35e5aca59af7e92afb2ee7bb821e))
