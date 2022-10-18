# Changelog

## [0.2.0](https://github.com/keptn-sandbox/lifecycle-controller/compare/v0.1.0...v0.2.0) (2022-10-12)


### Features

* Added tutorial for setting up observability example ([#145](https://github.com/keptn-sandbox/lifecycle-controller/issues/145)) ([28f5a9c](https://github.com/keptn-sandbox/lifecycle-controller/commit/28f5a9c24d031694e2066318bc85ae6e79dfd095))
* **main:** Make LFC development environment installable with one command ([#138](https://github.com/keptn-sandbox/lifecycle-controller/issues/138)) ([832ca37](https://github.com/keptn-sandbox/lifecycle-controller/commit/832ca37d5a19297a63e17a8d367c126af37275c4))
* **operator:** Add commit hash, buildtime, buildversion to OTel resource attributes ([#121](https://github.com/keptn-sandbox/lifecycle-controller/issues/121)) ([5a2ef61](https://github.com/keptn-sandbox/lifecycle-controller/commit/5a2ef61b965472cfe850672d04b4361f5d48ca0d))
* **operator:** Add Spans for handling webhook requests and inject TraceContext ([#115](https://github.com/keptn-sandbox/lifecycle-controller/issues/115)) ([812f2c5](https://github.com/keptn-sandbox/lifecycle-controller/commit/812f2c5d49314617cb9c7532262e15edecd9f078))
* **operator:** Add support for OTel collector ([#139](https://github.com/keptn-sandbox/lifecycle-controller/issues/139)) ([ac3f0d2](https://github.com/keptn-sandbox/lifecycle-controller/commit/ac3f0d222f43abff7f35f1eb8de5ec80ff7dd8dc))
* **operator:** Added metrics ([#55](https://github.com/keptn-sandbox/lifecycle-controller/issues/55)) ([f8a3cee](https://github.com/keptn-sandbox/lifecycle-controller/commit/f8a3ceea6d1628750e7c3a7c9cd3372642bd0611))
* **operator:** Introduce OTel tracing for Task controller ([#128](https://github.com/keptn-sandbox/lifecycle-controller/issues/128)) ([0baf7a9](https://github.com/keptn-sandbox/lifecycle-controller/commit/0baf7a9d8058877247bc264eb6fdb645b0a77a60))
* **operator:** Introduce OTel tracing for Workload controller ([#125](https://github.com/keptn-sandbox/lifecycle-controller/issues/125)) ([bc03709](https://github.com/keptn-sandbox/lifecycle-controller/commit/bc03709b744d61ad966b5fba9f70dbeaffa10119))
* **operator:** Introduce OTel tracing for WorkloadInstance controller ([#131](https://github.com/keptn-sandbox/lifecycle-controller/issues/131)) ([a195614](https://github.com/keptn-sandbox/lifecycle-controller/commit/a1956141fe80e5b1afd79fb33198313e1dbff7fa))
* **scheduler:** Add OTel Resource Attributes ([#147](https://github.com/keptn-sandbox/lifecycle-controller/issues/147)) ([b952156](https://github.com/keptn-sandbox/lifecycle-controller/commit/b9521568e95e7855ee4fef5d55559376e2d398d9))
* **scheduler:** Add support for OTel collector ([#146](https://github.com/keptn-sandbox/lifecycle-controller/issues/146)) ([9fd210d](https://github.com/keptn-sandbox/lifecycle-controller/commit/9fd210d0355e5d17316f5daa8a8e289a03755d46))
* **scheduler:** Add tracing support ([#129](https://github.com/keptn-sandbox/lifecycle-controller/issues/129)) ([60651d1](https://github.com/keptn-sandbox/lifecycle-controller/commit/60651d15c78f9e0aa786d4dd4836c9ae828b14f3))
* **scheduler:** Background check for pod status in permit plugin ([#124](https://github.com/keptn-sandbox/lifecycle-controller/issues/124)) ([97ceef6](https://github.com/keptn-sandbox/lifecycle-controller/commit/97ceef6938603e315c4e1c8d2bb697aabc3dd7f8))
* **scheduler:** Disable gRPC logs when creating OTLP exporter ([#151](https://github.com/keptn-sandbox/lifecycle-controller/issues/151)) ([d0f69b9](https://github.com/keptn-sandbox/lifecycle-controller/commit/d0f69b9509543a5a11f22e8940a71018509ba048))


### Bug Fixes

* **scheduler:** Create new context when starting background routine for pod checks ([#148](https://github.com/keptn-sandbox/lifecycle-controller/issues/148)) ([543ca87](https://github.com/keptn-sandbox/lifecycle-controller/commit/543ca876b27d90cb906ddb2643112a62dc923f56))
* **scheduler:** Ignoring OTel error logs ([#150](https://github.com/keptn-sandbox/lifecycle-controller/issues/150)) ([0be89a5](https://github.com/keptn-sandbox/lifecycle-controller/commit/0be89a56445a0356275f040dedad8fc8716a0fdd))


### Docs

* Add proper version badge in readme ([#114](https://github.com/keptn-sandbox/lifecycle-controller/issues/114)) ([e4add2d](https://github.com/keptn-sandbox/lifecycle-controller/commit/e4add2de2340f160fe30bd0cd6831107339b175e))
* Improve podtato example with HTTP service lookup ([#113](https://github.com/keptn-sandbox/lifecycle-controller/issues/113)) ([81b1236](https://github.com/keptn-sandbox/lifecycle-controller/commit/81b1236dcff7bd37afd0e39f11638fe01406c7c4))
* Update manifest name in readme ([#111](https://github.com/keptn-sandbox/lifecycle-controller/issues/111)) ([e51dbbc](https://github.com/keptn-sandbox/lifecycle-controller/commit/e51dbbc0198f734fb3905b280bc1ff2e0b24d39e))


### Other

* Updated scheduler readme and developer instructions ([#123](https://github.com/keptn-sandbox/lifecycle-controller/issues/123)) ([9bd5d14](https://github.com/keptn-sandbox/lifecycle-controller/commit/9bd5d1461cdeeca851b6ccb78ee7e6ff0b500c1c))


### Build

* Prepare release ([#149](https://github.com/keptn-sandbox/lifecycle-controller/issues/149)) ([5be4504](https://github.com/keptn-sandbox/lifecycle-controller/commit/5be4504e365b1c89ffc3069871a3f0fc0ecc7482))

## 0.1.0 (2022-10-04)


### Features

* Add scheduler with annotations ([#31](https://github.com/keptn-sandbox/lifecycle-controller/issues/31)) ([9e29019](https://github.com/keptn-sandbox/lifecycle-controller/commit/9e29019c098fd4f1d5e36500bd2c7ef410421aa8))
* Bootstrap Service CR and controller ([#21](https://github.com/keptn-sandbox/lifecycle-controller/issues/21)) ([c714ecc](https://github.com/keptn-sandbox/lifecycle-controller/commit/c714eccc3b9c4d1309036fc9d193da3154b4cac5))
* First draft of a scheduler ([#19](https://github.com/keptn-sandbox/lifecycle-controller/issues/19)) ([1884c86](https://github.com/keptn-sandbox/lifecycle-controller/commit/1884c8678a681ed322a0ef2ea07fad3e24e01237))
* first podtatohead sample deployment manifests ([#45](https://github.com/keptn-sandbox/lifecycle-controller/issues/45)) ([3e92d27](https://github.com/keptn-sandbox/lifecycle-controller/commit/3e92d277ebf1a9063ebcf80f05ebe62958e45cbb))
* First Version of Function Execution ([#35](https://github.com/keptn-sandbox/lifecycle-controller/issues/35)) ([f6badfd](https://github.com/keptn-sandbox/lifecycle-controller/commit/f6badfd19f9f0b15c04364be7b03f524c920a015))
* initial version of function runtime ([#26](https://github.com/keptn-sandbox/lifecycle-controller/issues/26)) ([c8800ee](https://github.com/keptn-sandbox/lifecycle-controller/commit/c8800ee352b5d0d5eccd7338cd4fa6a3ae7d2efa))
* Inject keptn-scheduler when resource contains Keptn annotations ([#18](https://github.com/keptn-sandbox/lifecycle-controller/issues/18)) ([4530e86](https://github.com/keptn-sandbox/lifecycle-controller/commit/4530e8602beb4fc923b767eb586e44752f725400))
* **lfc-scheduler:** Move from Helm to Kustomize ([#53](https://github.com/keptn-sandbox/lifecycle-controller/issues/53)) ([d7ba5f3](https://github.com/keptn-sandbox/lifecycle-controller/commit/d7ba5f35f1b32451f833d9fd53079b4162837bde))
* sample function for deno runtime ([#27](https://github.com/keptn-sandbox/lifecycle-controller/issues/27)) ([2501e46](https://github.com/keptn-sandbox/lifecycle-controller/commit/2501e46a18dfc4ab436669fa7c42c570abad5a52))
* substitute event task ([#43](https://github.com/keptn-sandbox/lifecycle-controller/issues/43)) ([3644a7d](https://github.com/keptn-sandbox/lifecycle-controller/commit/3644a7d9a0d4a565a9d857348a63ed91d8cb8102))
* Switch to distroless-base image ([#46](https://github.com/keptn-sandbox/lifecycle-controller/issues/46)) ([0a735b2](https://github.com/keptn-sandbox/lifecycle-controller/commit/0a735b2ca22a02ca42faf7d091741d39e0f5a547))
* Webhook creates Service, Service creates ServiceRun, ServiceRun creates Event ([#30](https://github.com/keptn-sandbox/lifecycle-controller/issues/30)) ([5ae58c3](https://github.com/keptn-sandbox/lifecycle-controller/commit/5ae58c33abe965e79bb405e74c0f308f1220d4ee))


### Bug Fixes

* Added namespace to task definition for podtato head example ([#72](https://github.com/keptn-sandbox/lifecycle-controller/issues/72)) ([7081f27](https://github.com/keptn-sandbox/lifecycle-controller/commit/7081f2772aee5abec840a58c7ab700603e84cf52))
* Fix CODEOWNERS syntax ([0be5197](https://github.com/keptn-sandbox/lifecycle-controller/commit/0be5197c19ea3066d28fe8e97f274efff21f66ff))
* fixed namespace in scheduler kustomization ([#63](https://github.com/keptn-sandbox/lifecycle-controller/issues/63)) ([237bf4f](https://github.com/keptn-sandbox/lifecycle-controller/commit/237bf4f480161f48aa0c4b5f2afbff433447d2a8))
* Missed error ([#76](https://github.com/keptn-sandbox/lifecycle-controller/issues/76)) ([a59aa15](https://github.com/keptn-sandbox/lifecycle-controller/commit/a59aa1552795bce15e39195af235fd42d1448e61))
* **operator:** Get desired amount of replicas from upper level resource ([#89](https://github.com/keptn-sandbox/lifecycle-controller/issues/89)) ([6767832](https://github.com/keptn-sandbox/lifecycle-controller/commit/67678327c2531c25ea0cdb6f1b805365ae454719))
* **operator:** Update workload if spec changes ([#90](https://github.com/keptn-sandbox/lifecycle-controller/issues/90)) ([ec01ad2](https://github.com/keptn-sandbox/lifecycle-controller/commit/ec01ad2ccd04f0c4e6f9ba47e01c5bada128aa3b))
* **operator:** Update workload instance controller, add example ([#102](https://github.com/keptn-sandbox/lifecycle-controller/issues/102)) ([e679c10](https://github.com/keptn-sandbox/lifecycle-controller/commit/e679c1070f0130bd2d6616bf1856956e64dc0bac))
* query jobs before creating ([#79](https://github.com/keptn-sandbox/lifecycle-controller/issues/79)) ([47f82b8](https://github.com/keptn-sandbox/lifecycle-controller/commit/47f82b891d9d20ade2928faae307009e5c96ae22))
* scheduler config plugin configuration ([#68](https://github.com/keptn-sandbox/lifecycle-controller/issues/68)) ([4c4e3c6](https://github.com/keptn-sandbox/lifecycle-controller/commit/4c4e3c60a0e11267dc69ea7d8470555e3ee4f91e))


### Miscellaneous Chores

* release 0.1.0 ([4c46a42](https://github.com/keptn-sandbox/lifecycle-controller/commit/4c46a4297c540b9da30c5a373624d4b8e8a88231))
* release 0.1.0 ([afa8493](https://github.com/keptn-sandbox/lifecycle-controller/commit/afa849324fa422352ed61faa7f0dc75d74c3c25d))


### Continuous Integration

* Prepare release ([#110](https://github.com/keptn-sandbox/lifecycle-controller/issues/110)) ([9d7644b](https://github.com/keptn-sandbox/lifecycle-controller/commit/9d7644b718e29bd37da398d89dc8b51997667358))

## Changelog