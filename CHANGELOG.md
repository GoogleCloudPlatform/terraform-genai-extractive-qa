# Changelog

## [0.3.1](https://github.com/GoogleCloudPlatform/terraform-genai-knowledge-base/compare/v0.3.0...v0.3.1) (2025-01-10)


### Bug Fixes

* Pin Google provider to 5.37.0 & set LOG_EXECUTION_ID ([#166](https://github.com/GoogleCloudPlatform/terraform-genai-knowledge-base/issues/166)) ([1ac2543](https://github.com/GoogleCloudPlatform/terraform-genai-knowledge-base/commit/1ac25438ad378313aa54a12b879cfe4291c75c84))

## [0.3.0](https://github.com/GoogleCloudPlatform/terraform-genai-knowledge-base/compare/v0.2.0...v0.3.0) (2024-05-29)


### Features

* add unique prefix to resource names ([#90](https://github.com/GoogleCloudPlatform/terraform-genai-knowledge-base/issues/90)) ([50ce35e](https://github.com/GoogleCloudPlatform/terraform-genai-knowledge-base/commit/50ce35ece4baf601053be1f643c60479ba7dc8d4))
* use gemini for tuning ([#125](https://github.com/GoogleCloudPlatform/terraform-genai-knowledge-base/issues/125)) ([9e18fea](https://github.com/GoogleCloudPlatform/terraform-genai-knowledge-base/commit/9e18feae6cac89bddf33d32271cdcf5409833a90))

## [0.2.0](https://github.com/GoogleCloudPlatform/terraform-genai-knowledge-base/compare/v0.1.1...v0.2.0) (2024-04-30)


### Features

* add notebook for predictions ([#78](https://github.com/GoogleCloudPlatform/terraform-genai-knowledge-base/issues/78)) ([1ebde35](https://github.com/GoogleCloudPlatform/terraform-genai-knowledge-base/commit/1ebde35e8802f243e36d483f6304cd704f5de703))
* add support for make it mine and deploy via cloudbuild trigger ([#96](https://github.com/GoogleCloudPlatform/terraform-genai-knowledge-base/issues/96)) ([bb0c209](https://github.com/GoogleCloudPlatform/terraform-genai-knowledge-base/commit/bb0c209e14a04b2c595e512ae369043ec230a38e))
* add vector search ([#43](https://github.com/GoogleCloudPlatform/terraform-genai-knowledge-base/issues/43)) ([257d718](https://github.com/GoogleCloudPlatform/terraform-genai-knowledge-base/commit/257d71817a22a4f3090de1f9dc4b92cd545b4f6d))
* improve image building performance ([#67](https://github.com/GoogleCloudPlatform/terraform-genai-knowledge-base/issues/67)) ([2723991](https://github.com/GoogleCloudPlatform/terraform-genai-knowledge-base/commit/2723991fce72604bc1d53a834b4a82ed3e99424c))
* terraform to auto deploy index ([#66](https://github.com/GoogleCloudPlatform/terraform-genai-knowledge-base/issues/66)) ([1f9caec](https://github.com/GoogleCloudPlatform/terraform-genai-knowledge-base/commit/1f9caecaf33448f3083cef3896f22225b3d39fb9))
* use document ai batch process ([#71](https://github.com/GoogleCloudPlatform/terraform-genai-knowledge-base/issues/71)) ([dcb2e48](https://github.com/GoogleCloudPlatform/terraform-genai-knowledge-base/commit/dcb2e48acf8915a85e868c454ba10af44eb00dd4))


### Bug Fixes

* back out unique names and use unique webhook_sa_name ([#87](https://github.com/GoogleCloudPlatform/terraform-genai-knowledge-base/issues/87)) ([eb6965c](https://github.com/GoogleCloudPlatform/terraform-genai-knowledge-base/commit/eb6965cec703528859fe503141308cb94a89ab7d))
* Fix Blueprint integration test ([#88](https://github.com/GoogleCloudPlatform/terraform-genai-knowledge-base/issues/88)) ([0457df4](https://github.com/GoogleCloudPlatform/terraform-genai-knowledge-base/commit/0457df4e39f9f83363cda303327b6f666045debf))
* Pin bigframes to &lt; 1.0.0 ([#91](https://github.com/GoogleCloudPlatform/terraform-genai-knowledge-base/issues/91)) ([e708452](https://github.com/GoogleCloudPlatform/terraform-genai-knowledge-base/commit/e708452c6fa6d1150d7041ad5f08a989f3ef607f))
* Pin bigframes to &lt;1.0.0 in notebook ([#92](https://github.com/GoogleCloudPlatform/terraform-genai-knowledge-base/issues/92)) ([fc0016f](https://github.com/GoogleCloudPlatform/terraform-genai-knowledge-base/commit/fc0016f30229f7631932c9823e9ad38aee932ea3))
* Set labels of all labels-supporting resources ([#95](https://github.com/GoogleCloudPlatform/terraform-genai-knowledge-base/issues/95)) ([4aa6b6c](https://github.com/GoogleCloudPlatform/terraform-genai-knowledge-base/commit/4aa6b6c64687d614febd8150a0664f24e35ae055))
* set unique_names to true ([#83](https://github.com/GoogleCloudPlatform/terraform-genai-knowledge-base/issues/83)) ([37a13fa](https://github.com/GoogleCloudPlatform/terraform-genai-knowledge-base/commit/37a13fa95d2d944ddad26c80ed0923620cc70699))
* Update architecture diagram ([#80](https://github.com/GoogleCloudPlatform/terraform-genai-knowledge-base/issues/80)) ([0a28eef](https://github.com/GoogleCloudPlatform/terraform-genai-knowledge-base/commit/0a28eef03e6bf7c6c6ec6727d10fc98a0a4359a6))

## [0.1.1](https://github.com/GoogleCloudPlatform/terraform-genai-knowledge-base/compare/v0.1.0...v0.1.1) (2023-12-08)


### Bug Fixes

* added envar for generating metadata ([#25](https://github.com/GoogleCloudPlatform/terraform-genai-knowledge-base/issues/25)) ([c208ebf](https://github.com/GoogleCloudPlatform/terraform-genai-knowledge-base/commit/c208ebf3fd8f96504c8f84f1415fef7a375aba8a))

## 0.1.0 (2023-12-01)


### Features

* added Firestore component ([124a6b1](https://github.com/GoogleCloudPlatform/terraform-genai-knowledge-base/commit/124a6b1df20d193bd1877930f18353ac9e2350d1))
* added README.md ([66ce9ba](https://github.com/GoogleCloudPlatform/terraform-genai-knowledge-base/commit/66ce9ba5457b6278981fe0f5adda865b44e9d93c))
* adds BQ file ([acdc411](https://github.com/GoogleCloudPlatform/terraform-genai-knowledge-base/commit/acdc411c5424cd4e06217db84dcf863dd7b23ec2))
* adds Firestore get QA count ([c5645fa](https://github.com/GoogleCloudPlatform/terraform-genai-knowledge-base/commit/c5645fa3b5a2c2e3e001d1e1cfe8e0044acd8add))
* adds Jupyter notebook to JSS ([#17](https://github.com/GoogleCloudPlatform/terraform-genai-knowledge-base/issues/17)) ([4097917](https://github.com/GoogleCloudPlatform/terraform-genai-knowledge-base/commit/4097917807c6d24d37386c8376078791310486e2))
* adds Vision OCR ([7f22f33](https://github.com/GoogleCloudPlatform/terraform-genai-knowledge-base/commit/7f22f33c3ec4d853f53d99bb7ca048f829fb3a49))
* changes to address service test ([3433aa0](https://github.com/GoogleCloudPlatform/terraform-genai-knowledge-base/commit/3433aa0cbec9c0d3f610c23d3d8d64d179517e76))
* consolidated logger names ([#22](https://github.com/GoogleCloudPlatform/terraform-genai-knowledge-base/issues/22)) ([ee8ed5b](https://github.com/GoogleCloudPlatform/terraform-genai-knowledge-base/commit/ee8ed5b5b0ac4a0389bbb1cf97b3756bbfdb2897))
* final polish of notebook; clean up ([#45](https://github.com/GoogleCloudPlatform/terraform-genai-knowledge-base/issues/45)) ([6687fcb](https://github.com/GoogleCloudPlatform/terraform-genai-knowledge-base/commit/6687fcbf212f0e6b400118ac3c24a468a54c43e2))
* gets all QAs from Firestore ([5d279ef](https://github.com/GoogleCloudPlatform/terraform-genai-knowledge-base/commit/5d279ef1bb76b44a6d22dbdd505036e72e59d00b))
* sic metadata gen and ingestion ([#34](https://github.com/GoogleCloudPlatform/terraform-genai-knowledge-base/issues/34)) ([ccfe4a4](https://github.com/GoogleCloudPlatform/terraform-genai-knowledge-base/commit/ccfe4a4b330fd76b22a0f16aa8694d3540c0f341))
* upload and refactor of code ([19530e3](https://github.com/GoogleCloudPlatform/terraform-genai-knowledge-base/commit/19530e3e4875e66a8511e257fe92d826a5de6a45))
* webhook self call for Eventarc-triggered events ([#33](https://github.com/GoogleCloudPlatform/terraform-genai-knowledge-base/issues/33)) ([c86b3d6](https://github.com/GoogleCloudPlatform/terraform-genai-knowledge-base/commit/c86b3d6505ac06fe1b0bfb99d91b7593f3caa39f))
* wired up services to function ([f27e726](https://github.com/GoogleCloudPlatform/terraform-genai-knowledge-base/commit/f27e726dc657b6f1bf43b430c6190628f890b7e8))


### Bug Fixes

* add uuid suffix for unique bucket names ([#39](https://github.com/GoogleCloudPlatform/terraform-genai-knowledge-base/issues/39)) ([7b949a8](https://github.com/GoogleCloudPlatform/terraform-genai-knowledge-base/commit/7b949a8b04bc60b3eff624e6d9726e364317a54e))
* handle empty string case in extraction util ([#54](https://github.com/GoogleCloudPlatform/terraform-genai-knowledge-base/issues/54)) ([cb958b5](https://github.com/GoogleCloudPlatform/terraform-genai-knowledge-base/commit/cb958b5d86ba480d92d49ceb01695fb9f29f9bfc))
* make lint, cft tests happy ([#31](https://github.com/GoogleCloudPlatform/terraform-genai-knowledge-base/issues/31)) ([fd85536](https://github.com/GoogleCloudPlatform/terraform-genai-knowledge-base/commit/fd85536596fee6ae537e21893abd9364a2526033))
* refactor the LLM prompt to its own variable ([#65](https://github.com/GoogleCloudPlatform/terraform-genai-knowledge-base/issues/65)) ([4d20008](https://github.com/GoogleCloudPlatform/terraform-genai-knowledge-base/commit/4d200088bfea58af0fbfb769bfbfd360bf1c5fc3))
* Shorten storage bucket name ([#43](https://github.com/GoogleCloudPlatform/terraform-genai-knowledge-base/issues/43)) ([ce62b27](https://github.com/GoogleCloudPlatform/terraform-genai-knowledge-base/commit/ce62b276a840b56347bb4e119c3e8fda5ea31ec3))
* Update int.cloudbuild.yaml to use LR billing ([#61](https://github.com/GoogleCloudPlatform/terraform-genai-knowledge-base/issues/61)) ([810c052](https://github.com/GoogleCloudPlatform/terraform-genai-knowledge-base/commit/810c05202f35420616614cef57d7472151918750))
