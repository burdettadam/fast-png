<a name="2.0.0"></a>
# [2.0.0](https://github.com/image-js/fast-png/compare/v1.1.0...v2.0.0) (2017-07-12)


* add CRC calculation and fix 16-bit encoding ([d11fa54](https://github.com/image-js/fast-png/commit/d11fa54))


### Bug Fixes

* detect endianess of the platform in decoder ([4f74ee7](https://github.com/image-js/fast-png/commit/4f74ee7))


### Features

* add a checkCrc option to the decoder ([d920bc0](https://github.com/image-js/fast-png/commit/d920bc0)), closes [#7](https://github.com/image-js/fast-png/issues/7)
* add support for decoding pHYs chunk ([800d428](https://github.com/image-js/fast-png/commit/800d428))
* implement PNG encoder ([00d1e3c](https://github.com/image-js/fast-png/commit/00d1e3c))


### BREAKING CHANGES

* To be consistent with the encoder, the data array returned by the decoder
is now a Uint16Array for 16-bit images.



<a name="1.1.0"></a>
# [1.1.0](https://github.com/image-js/fast-png/compare/v1.0.0...v1.1.0) (2016-06-12)



<a name="1.0.0"></a>
# [1.0.0](https://github.com/image-js/fast-png/compare/v0.0.4...v1.0.0) (2015-11-23)



<a name="0.0.4"></a>
## [0.0.4](https://github.com/image-js/fast-png/compare/v0.0.3...v0.0.4) (2015-09-26)



<a name="0.0.3"></a>
## [0.0.3](https://github.com/image-js/fast-png/compare/v0.0.2...v0.0.3) (2015-09-26)



<a name="0.0.2"></a>
## [0.0.2](https://github.com/image-js/fast-png/compare/v0.0.1...v0.0.2) (2015-09-26)



<a name="0.0.1"></a>
## 0.0.1 (2015-09-26)


