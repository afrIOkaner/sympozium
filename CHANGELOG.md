# Changelog

## [0.8.13](https://github.com/afrIOkaner/sympozium/compare/v0.9.1...v0.8.13) (2026-04-19)


### ⚠ BREAKING CHANGES

* Ensemble CRD replaces PersonaPack (see commit 432355b).
* The PersonaPack CRD has been renamed to Ensemble. All API endpoints, labels, controllers, and UI references updated.

### Features

* add apiKey support for provider models fetching ([369fab3](https://github.com/afrIOkaner/sympozium/commit/369fab35e02dd9a5effadb9ce68ccd39d14f6b0e))
* add apiKey support for provider models fetching ([fb4bb53](https://github.com/afrIOkaner/sympozium/commit/fb4bb53b302ff0e11b176e9dba2e19a8856d2295))
* add apiKey support for provider models fetching ([f9b69a9](https://github.com/afrIOkaner/sympozium/commit/f9b69a95f681ee0384b0e63e018750ac3aaab441))
* add channel access control with sender/chat allowlists and denylists ([b6310ec](https://github.com/afrIOkaner/sympozium/commit/b6310ec55df556a608dd2b6c4867cc3f1d4a454e)), closes [#43](https://github.com/afrIOkaner/sympozium/issues/43)
* add Cypress UX tests for instance creation and persona packs ([2ffb502](https://github.com/afrIOkaner/sympozium/commit/2ffb5026b82b116ab027c09bed58be9b9a02e8f1))
* add Cypress UX tests for instance creation and persona packs ([55e5590](https://github.com/afrIOkaner/sympozium/commit/55e5590af21dbea24e594ec7437052cc89ded4dc))
* add developer-team PersonaPack, software-dev skill, and Helm persona support ([9b53ccb](https://github.com/afrIOkaner/sympozium/commit/9b53ccb538edb9dfc90356121e5e297cec3cdaab))
* add gateway observability dashboard and serving agents chart line ([bc5c737](https://github.com/afrIOkaner/sympozium/commit/bc5c73740dd1855690d240fec2e02c17113580d6))
* add GitHub repo + team instructions to all onboarding flows ([4ade0fa](https://github.com/afrIOkaner/sympozium/commit/4ade0fa5f51ec5d951370a76887ab3f43b91a01e))
* add GitHub repo step to onboarding wizards ([4a74d84](https://github.com/afrIOkaner/sympozium/commit/4a74d8441c8f6db6020a450d23401d9bbb9c2756))
* add Helm chart repository via GitHub Pages ([a589e82](https://github.com/afrIOkaner/sympozium/commit/a589e821bf112710dfc02bbc8bb22d1f7bbb9503))
* Add image pull secret propagation for agent run container ([51858a3](https://github.com/afrIOkaner/sympozium/commit/51858a3686d9a7593eaf20def93e77ad726825b6))
* Add image pull secret propagation for agentrun sidecar container ([d5f4852](https://github.com/afrIOkaner/sympozium/commit/d5f4852515320378b2a36a31a7ff3e6e083f0f9f))
* add inline editing for PersonaPack personas (system prompt & skills) ([6a46163](https://github.com/afrIOkaner/sympozium/commit/6a461631f871d343162da4ad09b49e2dadef2999))
* add llama-server as a first-class AI provider ([86ec4ae](https://github.com/afrIOkaner/sympozium/commit/86ec4ae6b202488ff5adfd012b9c790557d1a097))
* add LM Studio support for local inference ([53cc0f4](https://github.com/afrIOkaner/sympozium/commit/53cc0f4cf1385ff6b4a4041eccb842e556aa9e1e))
* add make web-dev-serve for rapid UX iteration ([e79af6c](https://github.com/afrIOkaner/sympozium/commit/e79af6ca37214b6862ad51d25776734bf93dfd6f))
* add node probe discovery to ensemble builder provider setup ([0576c7e](https://github.com/afrIOkaner/sympozium/commit/0576c7e44191d39e15c2ea7f5ef92a525d80724a))
* add Ollama support, fix network policies and web-proxy child runs ([0bdfaa5](https://github.com/afrIOkaner/sympozium/commit/0bdfaa55aa0b53fd989272382e5de72f627e8c00))
* add Open Graph and Twitter Card meta tags for link previews ([3f17f3b](https://github.com/afrIOkaner/sympozium/commit/3f17f3be0363db9cb6e5510140478234e82229e2))
* add persona pack bootstrap flow across namespaces ([dc7bdb6](https://github.com/afrIOkaner/sympozium/commit/dc7bdb634c52b246f4a832f6ee9361f4b4b26392))
* add persona relationships schema and workflow canvas ([ace2bcf](https://github.com/afrIOkaner/sympozium/commit/ace2bcf788612c25e28d0e3e8c582f973d80c90f))
* add PersonaPack CRD, reconciler, TUI personas view & channels edit tab ([3b26e27](https://github.com/afrIOkaner/sympozium/commit/3b26e2743abb7a783c82ae3a8eebb8ef3110017d))
* add provider icons to wizard dropdown and llama-server docs ([25fca6d](https://github.com/afrIOkaner/sympozium/commit/25fca6dfddf43c18725d6e8ef4f0fa963c097ed3))
* add RBAC permissions for metrics access on pods and nodes ([013b02e](https://github.com/afrIOkaner/sympozium/commit/013b02eede3918664eed3f0018d93e8d66782be8))
* add RBAC permissions for metrics access on pods and nodes ([d94ed79](https://github.com/afrIOkaner/sympozium/commit/d94ed79da573375e22186ebc8e6d5c264e56549d))
* add research-team PersonaPack with relationships and Cypress tests ([9357e0a](https://github.com/afrIOkaner/sympozium/commit/9357e0a2ec3fd0ac354ccc80da5c7c3a79db9d43))
* add REST API endpoints for schedules and personapacks ([fc41715](https://github.com/afrIOkaner/sympozium/commit/fc417157b3a7f57c6d6af604ab4846af61c79f20))
* add REST API endpoints for schedules and personapacks ([#8](https://github.com/afrIOkaner/sympozium/issues/8)) ([bc6c3f9](https://github.com/afrIOkaner/sympozium/commit/bc6c3f99d92e918660b6cf0473b5928a784ecf4f))
* add Settings page with Agent Sandbox CRD install/uninstall, MCP server auth & defaults ([833bbdc](https://github.com/afrIOkaner/sympozium/commit/833bbdce455457252b7ffc7abf879b74a98a13cd))
* add shared workflow memory for cross-persona knowledge sharing ([3a163dc](https://github.com/afrIOkaner/sympozium/commit/3a163dc5656e9cce1fa8cf5b2cd775e4f91f33a9))
* add SQLite-backed persistent memory with FTS5 search ([#45](https://github.com/afrIOkaner/sympozium/issues/45)) ([28013b7](https://github.com/afrIOkaner/sympozium/commit/28013b7f06299d4265fea0c12867ca4ab43e80ea))
* add sre observability skill and onboarding skill selection ([e00b996](https://github.com/afrIOkaner/sympozium/commit/e00b996c6154bafd2bbcbb0dfc781ce196320753))
* add tool-call circuit breaker and configurable run timeout ([b5a3b94](https://github.com/afrIOkaner/sympozium/commit/b5a3b94cefeb6c7cf68a1c6f90181a2f45f28344))
* add workflow relationships to developer-team ensemble ([49d8e85](https://github.com/afrIOkaner/sympozium/commit/49d8e851d14583d40ed8e8f7f42c77869cd0f4ad))
* added local development capabilities ([f59fb71](https://github.com/afrIOkaner/sympozium/commit/f59fb7181506b75e637b65e3ed3391697be13bff))
* added serving mode ([824a42e](https://github.com/afrIOkaner/sympozium/commit/824a42e1f116c52863e020846d51b13db0ac7044))
* adding actions update ([a26187d](https://github.com/afrIOkaner/sympozium/commit/a26187d4ef81e9b1c145cdeda913c969d6833b99))
* adding bedrock ([9359ab1](https://github.com/afrIOkaner/sympozium/commit/9359ab1aea71f2347e38a8a56ca0fa844ae41473))
* adding mcp docs ([9c8955d](https://github.com/afrIOkaner/sympozium/commit/9c8955def47291e3101a6e3dbb5f075b174b7dea))
* adding web ui ([6464912](https://github.com/afrIOkaner/sympozium/commit/6464912f8f6c9ebb361cef60fc78e4122fbd5134))
* agentsandboxing ([25c0bb2](https://github.com/afrIOkaner/sympozium/commit/25c0bb25bb2df5438072c931c8b8f05f3172d4f7))
* auto-detect Agent Sandbox CRDs and surface toggle in UI ([47d56ee](https://github.com/afrIOkaner/sympozium/commit/47d56eee03938cd03e13cd2d3b49a6102eb3ed13))
* auto-detect node probe providers and allow changing ensemble provider ([e79310f](https://github.com/afrIOkaner/sympozium/commit/e79310f0950c9d2e740f37dddc70b4ba2f36f8fb))
* AwaitingDelegate phase, Cypress workflow tests, hooks fix ([8fee27b](https://github.com/afrIOkaner/sympozium/commit/8fee27b9645729c6990d3471dd2240224f26c6c2))
* bumped llmfit skill version number ([e0c3122](https://github.com/afrIOkaner/sympozium/commit/e0c3122829b2f34ef9aee3f0bc92d9eefeccf1c5))
* delegate_to_persona tool and dashboard team canvas widget ([5b25b59](https://github.com/afrIOkaner/sympozium/commit/5b25b596c956ea3896d14a5d8d64d81177b0db6b))
* doc colors ([54178f7](https://github.com/afrIOkaner/sympozium/commit/54178f736f2ba28f4ff34b1b06280e5dd7cae52e))
* enhanced dashboard with OTEL observability panels and draggable layout ([c839f33](https://github.com/afrIOkaner/sympozium/commit/c839f335d11666eea4582243a4d3c264ab018afe))
* expose run timeout in web UI and CLI TUI ([3bca472](https://github.com/afrIOkaner/sympozium/commit/3bca472642dcf85df6a4f6d0f242f2ed08e3553e))
* fixed markdown rendering ([3f8d9ff](https://github.com/afrIOkaner/sympozium/commit/3f8d9ff68524dbf3108a6384531b6c41fa746891))
* fixed team instructions ([090ce37](https://github.com/afrIOkaner/sympozium/commit/090ce37f53be74792698d0902f2af7724492003c))
* fixed team instructions ([80deda3](https://github.com/afrIOkaner/sympozium/commit/80deda3e0ce314ba677232961469bec8ffdcada1))
* fixed token auth ([93cd905](https://github.com/afrIOkaner/sympozium/commit/93cd9052e663628e3790c65de27deea0ee2b6fcb))
* fixes to otel missing telemetry in UX ([f4c17b2](https://github.com/afrIOkaner/sympozium/commit/f4c17b27476ee417e9f94709a3e23ec8f2e48b93))
* fmt code ([f6f61c3](https://github.com/afrIOkaner/sympozium/commit/f6f61c39e008fc489b2a5ad27ed1bb86295cc8f3))
* fmt code ([fee9454](https://github.com/afrIOkaner/sympozium/commit/fee9454e5cf31cd8e4b8e7e067ba8271bb4ee036))
* fmted ([e2b41fc](https://github.com/afrIOkaner/sympozium/commit/e2b41fc19aec1edd98e9d788790c0507b571c055))
* **gate:** add response gate hooks with manual approval flow ([0e5ad97](https://github.com/afrIOkaner/sympozium/commit/0e5ad9718826a2b0b776131890a6aad9dcaa5a49))
* global persona canvas and live run status highlighting ([5e69827](https://github.com/afrIOkaner/sympozium/commit/5e69827d36f4e7d9c053c29631ef4071e46833a3))
* implement sequential workflow trigger in controller ([c5b9e45](https://github.com/afrIOkaner/sympozium/commit/c5b9e456f78261a35043e45e672342dc3eeac0f0))
* improving test quality ([ccecf51](https://github.com/afrIOkaner/sympozium/commit/ccecf5105e54276602a4394695abea9fd49503fe))
* improving UX ([da42c7f](https://github.com/afrIOkaner/sympozium/commit/da42c7f38ac57672a575d37090639a607b9a2fe5))
* improving UX + whatsapp ([1483d2a](https://github.com/afrIOkaner/sympozium/commit/1483d2a9cd62688c095b41d9e395895ec1fc749c))
* installed status for lm studio ([1e55013](https://github.com/afrIOkaner/sympozium/commit/1e5501346cb5bc51f8f77e6583ecaa1748c06f22))
* integration tests ([19a8425](https://github.com/afrIOkaner/sympozium/commit/19a842550c2f1492be78f46a17df1dd4feb79e53))
* integration tests ([0756599](https://github.com/afrIOkaner/sympozium/commit/0756599ada7930565901eb01591c2a7d8fa8851c))
* interactive canvas editing and persona-targeted spawning ([c3af2ea](https://github.com/afrIOkaner/sympozium/commit/c3af2ea143186de52c9f99f6e499cf48a646a860))
* lifecycle hooks — preRun and postRun containers for agent runs ([a29a8c9](https://github.com/afrIOkaner/sympozium/commit/a29a8c99a67287f063f2b1398b9e499b57e51d35))
* lifecycle hooks — preRun and postRun containers for agent runs ([#67](https://github.com/afrIOkaner/sympozium/issues/67)) ([46250af](https://github.com/afrIOkaner/sympozium/commit/46250afb1e379378e0a82d1d450a811f0a2181dc))
* llmfit skill ([a3b9327](https://github.com/afrIOkaner/sympozium/commit/a3b93275468481eada5e3e66258494b7be00579a))
* local dev improvements ([9a6d3a6](https://github.com/afrIOkaner/sympozium/commit/9a6d3a697c6bde2bfb854f7821c129bd795f831c))
* **makefile:** add ux-tests-serve target for running Cypress against sympozium serve ([e9c3202](https://github.com/afrIOkaner/sympozium/commit/e9c3202d98105eff3d1b7d6008b9b4f7cd7a4d2e))
* namespace dropdown from K8s, feed instance selector, WebSocket auto-connect, sidebar contribute links ([a56b7a1](https://github.com/afrIOkaner/sympozium/commit/a56b7a1260e7588c3fa765e671d9749635435bc3))
* node-probe reverse proxy and keyless provider support ([0a08529](https://github.com/afrIOkaner/sympozium/commit/0a085298246934c6703b20d132d1a8f6d005a8ed))
* **otel:** end-to-end trace propagation across channel → NATS → controller → agent ([6bff68a](https://github.com/afrIOkaner/sympozium/commit/6bff68a82e95556b9dee982f0a4ee82f368a9cad))
* **otel:** Epic 1 - add pkg/telemetry package + BMAD docs ([34d9411](https://github.com/afrIOkaner/sympozium/commit/34d9411d2b9d82e09c2a499da11733d3a5361053))
* **otel:** Epic 2 - controller OTel instrumentation + CRD ObservabilitySpec ([44ceb0c](https://github.com/afrIOkaner/sympozium/commit/44ceb0c6d172483e8c10d14288b348f20434aff2))
* **otel:** Epic 4 - API server OTel instrumentation ([7110ba2](https://github.com/afrIOkaner/sympozium/commit/7110ba223d1fdc9e5853eced387b5ef70197c70b))
* **otel:** Epic 5 - metrics instrumentation ([7c27700](https://github.com/afrIOkaner/sympozium/commit/7c2770021cf284e8ba29328063bd03c9e1c44856))
* **otel:** Epic 6 - structured logging with trace correlation ([9f4072b](https://github.com/afrIOkaner/sympozium/commit/9f4072b27358e81fcdea86f37ad15b767cff4211))
* **otel:** Epic 7 - configuration, Helm, and testing ([5542109](https://github.com/afrIOkaner/sympozium/commit/5542109c682c82a19386392a46fc7466847e47e8))
* **otel:** inject OTel env vars into channel pods + use configurable image registry ([9db9331](https://github.com/afrIOkaner/sympozium/commit/9db933122cab1307def08bf7f461b40bf5414b66))
* personas demo ([2c61809](https://github.com/afrIOkaner/sympozium/commit/2c6180990dd049598a65c178abe6378110d7d484))
* promote Team Canvas to prominent dashboard position ([958600a](https://github.com/afrIOkaner/sympozium/commit/958600a3e7cd7d3f506f62607a6e97ce466e965a))
* propagate auth, model, and channels from PersonaPack to instances ([4e8ccc9](https://github.com/afrIOkaner/sympozium/commit/4e8ccc99b559509ac9adff5f6091079476f44b15))
* **providers:** add Unsloth as a supported local LLM provider ([9c246c1](https://github.com/afrIOkaner/sympozium/commit/9c246c13ba8947b4fe026836e764786b43329126))
* real-time workflow canvas updates via WebSocket ([e3fe61f](https://github.com/afrIOkaner/sympozium/commit/e3fe61f2cfa3ef2d5e6ddaf6e5e215e1399afd35))
* rebase MCP bridge sidecar onto upstream/main ([5d1f215](https://github.com/afrIOkaner/sympozium/commit/5d1f21576385c8a12ad18addc74fa0197d710908))
* recover qwen-native tool_calls from reasoning_content ([f807de1](https://github.com/afrIOkaner/sympozium/commit/f807de172243672997d25c3cd311740b34396fcb))
* removed incorrect reference ([a825f91](https://github.com/afrIOkaner/sympozium/commit/a825f919f4478b25c1a24cf83daab608eb541406))
* rename PersonaPack to Ensemble + canvas-first builder ([432355b](https://github.com/afrIOkaner/sympozium/commit/432355bca86ddf8b78d4ac6ec5be708613634bcd))
* render markdown in feed pane and run detail page ([0c4d364](https://github.com/afrIOkaner/sympozium/commit/0c4d36422ad2a01e3fd6acd9a8261ed1958f6ed1))
* reworked memory implementation ([81fdd0c](https://github.com/afrIOkaner/sympozium/commit/81fdd0c83725dc068bc869f01b5d1af5c421c282))
* TUI persona wizard, install --image-tag, conflict-safe instance controller ([c2586fa](https://github.com/afrIOkaner/sympozium/commit/c2586fadd96bffcc4fc9250ec1d6cf10f0fc0d09))
* updated docs ([bbba829](https://github.com/afrIOkaner/sympozium/commit/bbba829d70182232954a93a261474703b851c532))
* updated logo ([2ed44ff](https://github.com/afrIOkaner/sympozium/commit/2ed44ffc0fad6109be0f21deb15c32ebe3aee473))
* updated logo in docs ([a614c20](https://github.com/afrIOkaner/sympozium/commit/a614c20de27b9593d246fc3f64d13a8fecaf6e39))
* updated logo in docs ([9014708](https://github.com/afrIOkaner/sympozium/commit/9014708ec941ead52a23ff419d85045dc213fff4))
* updated tests ([92255c7](https://github.com/afrIOkaner/sympozium/commit/92255c77fdb9e131b5d4666b8dc751ada35ee3da))
* updated ux ([425ed44](https://github.com/afrIOkaner/sympozium/commit/425ed44f9eabfa5841caba1e07ceaaba23d504b6))
* updated UX data ([3841ecc](https://github.com/afrIOkaner/sympozium/commit/3841eccd3902e216d3ccd2548c0f358aab910ecb))
* various fixes ([6abcc84](https://github.com/afrIOkaner/sympozium/commit/6abcc8455e1747146cf40501742878fe195582b8))
* web improvements ([ed68c62](https://github.com/afrIOkaner/sympozium/commit/ed68c62fb1a5e2951988a0db317a0f59fd89ebee))
* web UX overhaul — onboarding wizard, feed pane, model auto-populate, auth fixes ([e095eec](https://github.com/afrIOkaner/sympozium/commit/e095eece095e7a013d88adbf2acb7d6a9c86b821))
* **web:** add run notifications, unseen watermark, and polling ([42bb00b](https://github.com/afrIOkaner/sympozium/commit/42bb00b9cceae427a0ce3a0c2b12895b94e5e6af))
* **web:** improve sidebar hierarchy, breadcrumbs, and detail page UX ([0a622d1](https://github.com/afrIOkaner/sympozium/commit/0a622d176c0ee0ad536273d5eb61c277a5e778d1))
* working on gateway ([5dc3931](https://github.com/afrIOkaner/sympozium/commit/5dc39311b6b5168d01f131df7c0bd4779ec67b04))


### Bug Fixes

* add mcp-bridge to release image matrix ([0575e8c](https://github.com/afrIOkaner/sympozium/commit/0575e8cec412b22de9e674d2c9450f1e66b22de1))
* add metrics.k8s.io RBAC to config/rbac/role.yaml for sympozium install ([0c1a51c](https://github.com/afrIOkaner/sympozium/commit/0c1a51c8d11354aa5e2df694e8557c120b474857))
* add missing MCP server resources to ClusterRole ([0f0786b](https://github.com/afrIOkaner/sympozium/commit/0f0786b5500a3357c5c31b0046caffc8e9df6d3a))
* add missing MCP server resources to ClusterRole ([6a4c744](https://github.com/afrIOkaner/sympozium/commit/6a4c744b6ac3b532a017801e058b923b038544d1))
* add missing observability-mcp-team persona pack to Helm chart ([fc0105c](https://github.com/afrIOkaner/sympozium/commit/fc0105c0d243bb0adc58680e29a4827b7aad88bd))
* add missing RBAC resources for sympozium install ([d41f6aa](https://github.com/afrIOkaner/sympozium/commit/d41f6aacd120c640f3aba61a358690e758479c68))
* add missing RBAC resources for sympozium install ([#9](https://github.com/afrIOkaner/sympozium/issues/9)) ([3a90279](https://github.com/afrIOkaner/sympozium/commit/3a902795d05ff94e5470e3cf51c830df3aec7fc8))
* add missing ServiceAccounts and ClusterRoleBinding ([8bbd4e0](https://github.com/afrIOkaner/sympozium/commit/8bbd4e0db9ad13c8ec44086dc5b651b38b3147f4))
* add namespace selection to onboard wizard ([a153585](https://github.com/afrIOkaner/sympozium/commit/a1535853089d0f17055f7ddb089b7c654f619fbc))
* add namespace selection to onboard wizard ([0349276](https://github.com/afrIOkaner/sympozium/commit/0349276d990580e2ffbbd0f8b14446eb8ca663d5)), closes [#24](https://github.com/afrIOkaner/sympozium/issues/24)
* add namespace to default PersonaPack manifests ([25b490a](https://github.com/afrIOkaner/sympozium/commit/25b490ad0ad8ee47aa00b9725c5a19521bd9c50f))
* add new guides and agent-sandbox to mkdocs nav ([efebd3b](https://github.com/afrIOkaner/sympozium/commit/efebd3b911a576a7174a52a0e7528a649caa1a93))
* add part-of label to agent pods so OTEL network policy applies ([eebaf9d](https://github.com/afrIOkaner/sympozium/commit/eebaf9d9a959acb7381e7d672bee7e3b58f851ee))
* adding network policy issues ([c925d19](https://github.com/afrIOkaner/sympozium/commit/c925d194e21944d6e54d2b0886b02c2ee7e699e9))
* address PR [#18](https://github.com/afrIOkaner/sympozium/issues/18) review feedback ([3356f9c](https://github.com/afrIOkaner/sympozium/commit/3356f9c8f4ff64003b0d3638a5824248b06c0e51))
* AgentRun status concurrency update ([87dbb22](https://github.com/afrIOkaner/sympozium/commit/87dbb2226b22de4106d7c7c90fb77101c4217f38))
* align Agent Sandbox with upstream agents.x-k8s.io API group ([0cd4d69](https://github.com/afrIOkaner/sympozium/commit/0cd4d6928d794920ca9121f0751caa8c45949d8d))
* align ObservabilitySpec field names with updated CRD ([d49da0e](https://github.com/afrIOkaner/sympozium/commit/d49da0e0cb6265cec07250dae6bd08f4d65f52f6))
* allow Kubernetes API server egress on non-standard ports ([a53c934](https://github.com/afrIOkaner/sympozium/commit/a53c934267ef442b8f927bee49fe8e6ebd68fe94))
* allow Kubernetes API server egress on non-standard ports ([80ed8ab](https://github.com/afrIOkaner/sympozium/commit/80ed8ab7d3939bd7da2d9d14dc90f267e1a85ba0)), closes [#26](https://github.com/afrIOkaner/sympozium/issues/26)
* apiserver WebSocket stability and cross-namespace skill/policy listing ([d4a71a4](https://github.com/afrIOkaner/sympozium/commit/d4a71a44c328058f751db23466309a40b86276d9))
* auto-create K8s Secret from API key during persona activation ([7f7a487](https://github.com/afrIOkaner/sympozium/commit/7f7a487987ca5f9096bc11227bfb8211d29e430f))
* auto-reconnect port-forward and retry network errors ([b0ec3b6](https://github.com/afrIOkaner/sympozium/commit/b0ec3b6d6f1eaea5eeea4cc2d8b24f309aa11f1b))
* auto-store task/response in memory server after each agent run ([8f475fb](https://github.com/afrIOkaner/sympozium/commit/8f475fbc2bf600ca7fad12394e7c417dd63e2509))
* canvas empty state — use controlled ReactFlow props for read-only canvases ([58697be](https://github.com/afrIOkaner/sympozium/commit/58697bef2f880488db35c81c82a7a0370fa69f71))
* cascade-delete scheduled AgentRuns when their Schedule is removed ([eb1ad6a](https://github.com/afrIOkaner/sympozium/commit/eb1ad6af113686ae5b77c5d3b28c4ba9a913aabb))
* chain release workflow from release-please via workflow_call ([22c9e1e](https://github.com/afrIOkaner/sympozium/commit/22c9e1e9a17a52907e6c3424855bc82ce1cfb5b1))
* change SamplingRatio from *float64 to string for controller-gen compat ([9b79002](https://github.com/afrIOkaner/sympozium/commit/9b79002616317e950aa119f19f00cde0cdd407ee))
* channel status never persisted, always shown as "Unknown" ([#25](https://github.com/afrIOkaner/sympozium/issues/25)) ([065a9bb](https://github.com/afrIOkaner/sympozium/commit/065a9bb5e71465c881ac59ee2eba4108fa468f57))
* **ci:** include config/personas/ in release tarball ([d3b1721](https://github.com/afrIOkaner/sympozium/commit/d3b1721c66a68fc691c0ceffcc3f79f17c9577c6))
* **ci:** include config/personas/ in release tarball ([011d4a1](https://github.com/afrIOkaner/sympozium/commit/011d4a108db7295e820be0b91c46ecf7a199b32a))
* clear ExcludePersonas when activating a PersonaPack ([4955916](https://github.com/afrIOkaner/sympozium/commit/49559166de451b906b37c463f240625acd81b96b))
* CRD detection false negatives and missing provider in instances list ([0ca8398](https://github.com/afrIOkaner/sympozium/commit/0ca8398f84b0d12d14b84bc89fb6841a6f95e628))
* create namespace before Helm config init to fix fresh installs ([e49fa50](https://github.com/afrIOkaner/sympozium/commit/e49fa50f26604688a1dcbba6a3d06543b0442ea8))
* default observability config on API-created instances ([4818cbf](https://github.com/afrIOkaner/sympozium/commit/4818cbf02ae64e8cdc883f5a5e6d0b2093540269))
* disable persona packs instead of deleting them ([8fdd3ad](https://github.com/afrIOkaner/sympozium/commit/8fdd3addcb5e0fd19e0038fe3c6b31a08a68b019))
* docs ([c5a5bdb](https://github.com/afrIOkaner/sympozium/commit/c5a5bdb232053c54fbf1321d6601d4ee14495997))
* expand controller ClusterRole for skill RBAC delegation ([1c2ba0f](https://github.com/afrIOkaner/sympozium/commit/1c2ba0f531da6c9720d637c2d80af6e074c2dc16))
* fail AgentRun when skill RBAC creation fails instead of silently continuing ([99ddb4d](https://github.com/afrIOkaner/sympozium/commit/99ddb4d698bedd758c7d5512e6da354dad5db754))
* fixing otel/memory ([26624aa](https://github.com/afrIOkaner/sympozium/commit/26624aaa5bd60548ac77851cbe8c4c779dec326f))
* format files ([82c867b](https://github.com/afrIOkaner/sympozium/commit/82c867b7b55fd9b1a4ed7151482a482aaaf3860b))
* gofmt formatting and fix tool span name in otel test ([31af488](https://github.com/afrIOkaner/sympozium/commit/31af488a60bdbbca8a6908c50ee6f70e455615c0))
* guard stale Job-not-found reconcile during postRun transition ([8d2ff41](https://github.com/afrIOkaner/sympozium/commit/8d2ff41972acb551a9aabc13cc02c1807ca50560))
* handle OTEL collector cold start in observability integration test ([a52406a](https://github.com/afrIOkaner/sympozium/commit/a52406a31df3338c876991c92ff60898881fc7df))
* heredoc syntax error in ux-test preflight script ([abd0f5d](https://github.com/afrIOkaner/sympozium/commit/abd0f5d5cad7eff3e3983b0ec1603b547e6cc8f6))
* include node-probe in release manifests and use localhost for probe targets ([b45749d](https://github.com/afrIOkaner/sympozium/commit/b45749d3c0d8d4b5f61bf0e3589c8db4026b0a77))
* install built-in SympoziumPolicies during sympozium install and Helm deploy ([a6d2499](https://github.com/afrIOkaner/sympozium/commit/a6d2499e4c361a179078cd94754977f12ad18db7))
* **install:** disable chart namespace template to avoid collision ([e0aae1c](https://github.com/afrIOkaner/sympozium/commit/e0aae1c3a54a95ee6bd5a8d0a2cf1c9c5d9b4b50))
* **install:** recover from failed releases and simplify ns creation ([4c84612](https://github.com/afrIOkaner/sympozium/commit/4c846129d61b99829ef7219c7dc1ed7c4edb6607))
* missing image ([8a8c05b](https://github.com/afrIOkaner/sympozium/commit/8a8c05b9e1ce43c6f51969b32dfc6d34d6a3a5e9))
* multi-arch Docker builds and IPv4 port-forward binding ([c25d378](https://github.com/afrIOkaner/sympozium/commit/c25d378a4d09800f842b5d2a4eeb163777e34863))
* nil pointer dereference in admission webhook decoder ([538c6a0](https://github.com/afrIOkaner/sympozium/commit/538c6a021783ee818a4d78cb881c4f435f642085))
* nil pointer dereference in admission webhook decoder ([bc90f2c](https://github.com/afrIOkaner/sympozium/commit/bc90f2c5f68308191b0101d761b7862918f546c5)), closes [#29](https://github.com/afrIOkaner/sympozium/issues/29)
* node-probe crashloop caused by circular logger reference ([b3068da](https://github.com/afrIOkaner/sympozium/commit/b3068da172c2fe7e8d93ac5c9dfc196e1f39a220))
* node-probe host detection, verbose logging, and LM Studio model listing ([deb19a3](https://github.com/afrIOkaner/sympozium/commit/deb19a36431e9af20bac37062ccb72e36cebd009))
* node-probe issues ([41c13af](https://github.com/afrIOkaner/sympozium/commit/41c13afb8dd65e545aa27f49f9cf4858010f01ff))
* ollama specific test ([89290f6](https://github.com/afrIOkaner/sympozium/commit/89290f693ea72c6a5f334009d74f5c551ba6240d))
* only clear ExcludePersonas on first activation ([6d279a3](https://github.com/afrIOkaner/sympozium/commit/6d279a3c772baf7140620abf34c1929b7724e0e0))
* otel/memory write timeout ([2c0f848](https://github.com/afrIOkaner/sympozium/commit/2c0f84804cc490a53cd1acd30d1b7486bbe96bf3))
* persist baseURL from TUI persona wizard to PersonaPack spec ([186b1f8](https://github.com/afrIOkaner/sympozium/commit/186b1f80f79209d1be3d58160a3397003473fb1d)), closes [#39](https://github.com/afrIOkaner/sympozium/issues/39)
* **personas:** harden platform-team prompts + propagate systemPrompt edits ([079986d](https://github.com/afrIOkaner/sympozium/commit/079986d5e8edc00cd85cf9ed4d715b36f85a589b))
* populate auth/model/skills from instance when creating runs via API ([3577c5d](https://github.com/afrIOkaner/sympozium/commit/3577c5da1a4da965b0bea5ea5c923962ae44ec7e))
* populate default baseURL for local providers (Ollama, LM Studio) ([e9cd653](https://github.com/afrIOkaner/sympozium/commit/e9cd653b96a9e751a779194fc6d2bd70b69c36bc)), closes [#39](https://github.com/afrIOkaner/sympozium/issues/39)
* prevent apiserver image build timeout on multi-arch builds ([830329d](https://github.com/afrIOkaner/sympozium/commit/830329d94295f04a496594ff494100a9e48fd1e1)), closes [#60](https://github.com/afrIOkaner/sympozium/issues/60)
* prevent reconcile race from overriding Succeeded AgentRuns as Failed ([d681a33](https://github.com/afrIOkaner/sympozium/commit/d681a3359f1d64ec2d8755402c0abe3849d96e8a))
* propagate baseURL through personapack pipeline for local providers ([5025077](https://github.com/afrIOkaner/sympozium/commit/5025077347be219bd8c7fd022eab472d9b08c201))
* publish TopicAgentRunFailed from controller so web proxy unblocks on failure ([b98841f](https://github.com/afrIOkaner/sympozium/commit/b98841fe441a3c3f478640963c270fd7ed31dd85))
* regenerate deepcopy and sync CRDs/Helm ([5703c23](https://github.com/afrIOkaner/sympozium/commit/5703c23215ea4c2d02cf818fc4e101f1be3a77af))
* regenerate PersonaPack CRD to include baseURL field ([0650240](https://github.com/afrIOkaner/sympozium/commit/0650240706c8ca5c777d890a8de52fd7f914945b))
* remove conflicting namespace pre-creation in helm install ([9930ba4](https://github.com/afrIOkaner/sympozium/commit/9930ba4497989fa40d2461e9bef7039586c67aa0))
* remove explicit host from node-probe targets to restore auto-detection ([f91229a](https://github.com/afrIOkaner/sympozium/commit/f91229afa5ba5ad0674ba6c9b202932b2a869f3f))
* remove hardcoded dark fills from architecture diagrams ([328827b](https://github.com/afrIOkaner/sympozium/commit/328827b6e6aa57da765953d3504b391cd6662a60))
* resolve all Cypress TypeScript errors ([008266e](https://github.com/afrIOkaner/sympozium/commit/008266efbcec1f39e4929c89c3bf79cb581e3d23))
* resolve integration test hang and flaky secret-not-found error ([2fb431f](https://github.com/afrIOkaner/sympozium/commit/2fb431f99b42e14f6f123dbf6f62229ea3a06db0))
* resolve remaining TypeScript index signature errors in yaml-panel ([8cea011](https://github.com/afrIOkaner/sympozium/commit/8cea0119064536a30ba8a1a15d119af73c9380a9))
* resolve TypeScript index signature errors in yaml-panel ([4a576a1](https://github.com/afrIOkaner/sympozium/commit/4a576a1b8db3f77c7ee6cb610b08f212b3ab9cd0))
* restore node-probe-daemonset.yaml removed during rebase ([1b3f81f](https://github.com/afrIOkaner/sympozium/commit/1b3f81fd80721438e2280f8486d026289d33a1ce))
* run only smoke tests in CI integration workflow ([bf1c293](https://github.com/afrIOkaner/sympozium/commit/bf1c293374c6a90fa842f704d99efbad45783fdd))
* scale down controller before stripping finalizers on uninstall ([ef8381f](https://github.com/afrIOkaner/sympozium/commit/ef8381fcadb372fb0a28c05fd076cc5229af9b06))
* scale down controller before stripping finalizers on uninstall ([a70f821](https://github.com/afrIOkaner/sympozium/commit/a70f821dcdf1511661f92bcc7ab9621c621d205f)), closes [#21](https://github.com/afrIOkaner/sympozium/issues/21)
* scheduler picks next free run-number suffix to avoid ghost runs ([205829a](https://github.com/afrIOkaner/sympozium/commit/205829a2c1525d2b2cf5fbdb09829b254790f601))
* show API key input for all credential-based providers ([e0bcf58](https://github.com/afrIOkaner/sympozium/commit/e0bcf586590fe9a6366ad1e5fa67598c7dcd2cd7)), closes [#37](https://github.com/afrIOkaner/sympozium/issues/37)
* skip Helm CreateNamespace when sympozium-system already exists ([e40b157](https://github.com/afrIOkaner/sympozium/commit/e40b157a238de6b91cd8f0e0e18c771eb66e5a0d))
* skip mcp-bridge skill in projected volume to prevent FailedMount ([7ad48f6](https://github.com/afrIOkaner/sympozium/commit/7ad48f6ae49a69df65fd90f76667b354f80a6211))
* **slack:** add ping/pong handlers and increase WebSocket read deadline to 120s ([86b7387](https://github.com/afrIOkaner/sympozium/commit/86b7387cf7ab779345e54a2a9e69759c0d255f4d))
* split architecture diagram into readable sections and fix middot entity ([bc2be59](https://github.com/afrIOkaner/sympozium/commit/bc2be594b447d3d7fba4dd20bbb045bdc2725760))
* stabilize workflow canvas layout across data refreshes ([b83378a](https://github.com/afrIOkaner/sympozium/commit/b83378a1ff88c4546781598fc4bd52e65dd22ce9))
* stop Helm template from overriding node-probe host auto-detection ([4f0e5f4](https://github.com/afrIOkaner/sympozium/commit/4f0e5f41217d5ec9bf165dda7796be0df3fd307d))
* strip directory prefix from CRD names when writing to temp dir ([1906327](https://github.com/afrIOkaner/sympozium/commit/1906327b3abd32dc887f5a09c98eada9e0fb09b6))
* strip finalizers before controller deletion to prevent stuck resources ([d70a46d](https://github.com/afrIOkaner/sympozium/commit/d70a46dc0459d2ceca03daf257c5b8efc0abec52))
* surface reasoning-model responses when terminal turn is empty ([045f7d7](https://github.com/afrIOkaner/sympozium/commit/045f7d74a2f95b5ebab7eba392c6d4441734368b))
* sync RBAC markers with Helm chart permissions ([701a05a](https://github.com/afrIOkaner/sympozium/commit/701a05a6a4bee92d0dbbd2d54cdcede62c3424d7))
* tidy fmt ([0dec3eb](https://github.com/afrIOkaner/sympozium/commit/0dec3ebd96876e2433747decaa65b97388b91259))
* trigger docs rebuild after Helm chart publish ([9b0e03c](https://github.com/afrIOkaner/sympozium/commit/9b0e03c8a10c477f0e64995ca578c4a15021eccd))
* update all stale Persona Pack UI strings to Ensemble ([12fdaec](https://github.com/afrIOkaner/sympozium/commit/12fdaec4c6f73cc9f9febe87bd9d3ed61644f3ed))
* update API key retrieval to use header instead of query parameter ([e320e8d](https://github.com/afrIOkaner/sympozium/commit/e320e8d8361107acf30af4d35b9df2cd866c0cda))
* update API key retrieval to use header instead of query parameter ([ba6281a](https://github.com/afrIOkaner/sympozium/commit/ba6281a546a18f2b42193c5203049b08eb4eb983))
* update RBAC rules to include metrics.k8s.io permissions for skill sidecars ([cad5b4a](https://github.com/afrIOkaner/sympozium/commit/cad5b4a7eef051efd239604e472be905b4d28d21))
* update RBAC rules to include metrics.k8s.io permissions for skill sidecars ([3f90317](https://github.com/afrIOkaner/sympozium/commit/3f90317d172cc8d43a0d37b952196f48b3f73fe5))
* use sentinel value for run timeout Select to avoid Radix crash ([1553b75](https://github.com/afrIOkaner/sympozium/commit/1553b75912c1ed4037bd622de09abeaed57f290d))
* validate instance name as RFC 1123 subdomain in wizard ([714a405](https://github.com/afrIOkaner/sympozium/commit/714a4059ebd356e434bdfe941ed68cf1ca2501e7))
* web-proxy RBAC and getInstance to use namespaced Get ([0bb3e81](https://github.com/afrIOkaner/sympozium/commit/0bb3e815175d71272422c3fca49500104a204394))


### Miscellaneous Chores

* release 0.8.13 ([8a6fa7b](https://github.com/afrIOkaner/sympozium/commit/8a6fa7b870da36f0df6ab0bcccaeda6b1f04fec4))

## [0.9.1](https://github.com/sympozium-ai/sympozium/compare/v0.9.0...v0.9.1) (2026-04-19)


### Features

* add node probe discovery to ensemble builder provider setup ([0576c7e](https://github.com/sympozium-ai/sympozium/commit/0576c7e44191d39e15c2ea7f5ef92a525d80724a))
* add workflow relationships to developer-team ensemble ([49d8e85](https://github.com/sympozium-ai/sympozium/commit/49d8e851d14583d40ed8e8f7f42c77869cd0f4ad))
* auto-detect node probe providers and allow changing ensemble provider ([e79310f](https://github.com/sympozium-ai/sympozium/commit/e79310f0950c9d2e740f37dddc70b4ba2f36f8fb))


### Bug Fixes

* heredoc syntax error in ux-test preflight script ([abd0f5d](https://github.com/sympozium-ai/sympozium/commit/abd0f5d5cad7eff3e3983b0ec1603b547e6cc8f6))
* stabilize workflow canvas layout across data refreshes ([b83378a](https://github.com/sympozium-ai/sympozium/commit/b83378a1ff88c4546781598fc4bd52e65dd22ce9))

## [0.9.0](https://github.com/sympozium-ai/sympozium/compare/v0.8.28...v0.9.0) (2026-04-19)


### ⚠ BREAKING CHANGES

* Ensemble CRD replaces PersonaPack (see commit 432355b).
* The PersonaPack CRD has been renamed to Ensemble. All API endpoints, labels, controllers, and UI references updated.

### Features

* add shared workflow memory for cross-persona knowledge sharing ([3a163dc](https://github.com/sympozium-ai/sympozium/commit/3a163dc5656e9cce1fa8cf5b2cd775e4f91f33a9))
* implement sequential workflow trigger in controller ([c5b9e45](https://github.com/sympozium-ai/sympozium/commit/c5b9e456f78261a35043e45e672342dc3eeac0f0))
* real-time workflow canvas updates via WebSocket ([e3fe61f](https://github.com/sympozium-ai/sympozium/commit/e3fe61f2cfa3ef2d5e6ddaf6e5e215e1399afd35))
* rename PersonaPack to Ensemble + canvas-first builder ([432355b](https://github.com/sympozium-ai/sympozium/commit/432355bca86ddf8b78d4ac6ec5be708613634bcd))


### Bug Fixes

* resolve all Cypress TypeScript errors ([008266e](https://github.com/sympozium-ai/sympozium/commit/008266efbcec1f39e4929c89c3bf79cb581e3d23))
* update all stale Persona Pack UI strings to Ensemble ([12fdaec](https://github.com/sympozium-ai/sympozium/commit/12fdaec4c6f73cc9f9febe87bd9d3ed61644f3ed))

## [0.8.28](https://github.com/sympozium-ai/sympozium/compare/v0.8.27...v0.8.28) (2026-04-16)


### Features

* promote Team Canvas to prominent dashboard position ([958600a](https://github.com/sympozium-ai/sympozium/commit/958600a3e7cd7d3f506f62607a6e97ce466e965a))

## [0.8.27](https://github.com/sympozium-ai/sympozium/compare/v0.8.26...v0.8.27) (2026-04-16)


### Features

* add persona relationships schema and workflow canvas ([ace2bcf](https://github.com/sympozium-ai/sympozium/commit/ace2bcf788612c25e28d0e3e8c582f973d80c90f))
* add research-team PersonaPack with relationships and Cypress tests ([9357e0a](https://github.com/sympozium-ai/sympozium/commit/9357e0a2ec3fd0ac354ccc80da5c7c3a79db9d43))
* AwaitingDelegate phase, Cypress workflow tests, hooks fix ([8fee27b](https://github.com/sympozium-ai/sympozium/commit/8fee27b9645729c6990d3471dd2240224f26c6c2))
* delegate_to_persona tool and dashboard team canvas widget ([5b25b59](https://github.com/sympozium-ai/sympozium/commit/5b25b596c956ea3896d14a5d8d64d81177b0db6b))
* global persona canvas and live run status highlighting ([5e69827](https://github.com/sympozium-ai/sympozium/commit/5e69827d36f4e7d9c053c29631ef4071e46833a3))
* interactive canvas editing and persona-targeted spawning ([c3af2ea](https://github.com/sympozium-ai/sympozium/commit/c3af2ea143186de52c9f99f6e499cf48a646a860))


### Bug Fixes

* canvas empty state — use controlled ReactFlow props for read-only canvases ([58697be](https://github.com/sympozium-ai/sympozium/commit/58697bef2f880488db35c81c82a7a0370fa69f71))

## [0.8.26](https://github.com/sympozium-ai/sympozium/compare/v0.8.25...v0.8.26) (2026-04-16)


### Features

* add Settings page with Agent Sandbox CRD install/uninstall, MCP server auth & defaults ([833bbdc](https://github.com/sympozium-ai/sympozium/commit/833bbdce455457252b7ffc7abf879b74a98a13cd))


### Bug Fixes

* validate instance name as RFC 1123 subdomain in wizard ([714a405](https://github.com/sympozium-ai/sympozium/commit/714a4059ebd356e434bdfe941ed68cf1ca2501e7))

## [0.8.25](https://github.com/sympozium-ai/sympozium/compare/v0.8.24...v0.8.25) (2026-04-12)


### Features

* add provider icons to wizard dropdown and llama-server docs ([25fca6d](https://github.com/sympozium-ai/sympozium/commit/25fca6dfddf43c18725d6e8ef4f0fa963c097ed3))

## [0.8.24](https://github.com/sympozium-ai/sympozium/compare/v0.8.23...v0.8.24) (2026-04-12)


### Features

* add llama-server as a first-class AI provider ([86ec4ae](https://github.com/sympozium-ai/sympozium/commit/86ec4ae6b202488ff5adfd012b9c790557d1a097))
* fmt code ([f6f61c3](https://github.com/sympozium-ai/sympozium/commit/f6f61c39e008fc489b2a5ad27ed1bb86295cc8f3))

## [0.8.23](https://github.com/sympozium-ai/sympozium/compare/v0.8.22...v0.8.23) (2026-04-11)


### Bug Fixes

* **install:** disable chart namespace template to avoid collision ([e0aae1c](https://github.com/sympozium-ai/sympozium/commit/e0aae1c3a54a95ee6bd5a8d0a2cf1c9c5d9b4b50))
* **install:** recover from failed releases and simplify ns creation ([4c84612](https://github.com/sympozium-ai/sympozium/commit/4c846129d61b99829ef7219c7dc1ed7c4edb6607))

## [0.8.22](https://github.com/sympozium-ai/sympozium/compare/v0.8.21...v0.8.22) (2026-04-10)


### Features

* fmt code ([fee9454](https://github.com/sympozium-ai/sympozium/commit/fee9454e5cf31cd8e4b8e7e067ba8271bb4ee036))

## [0.8.21](https://github.com/sympozium-ai/sympozium/compare/v0.8.20...v0.8.21) (2026-04-10)


### Features

* **gate:** add response gate hooks with manual approval flow ([0e5ad97](https://github.com/sympozium-ai/sympozium/commit/0e5ad9718826a2b0b776131890a6aad9dcaa5a49))

## [0.8.20](https://github.com/sympozium-ai/sympozium/compare/v0.8.19...v0.8.20) (2026-04-07)


### Features

* **web:** add run notifications, unseen watermark, and polling ([42bb00b](https://github.com/sympozium-ai/sympozium/commit/42bb00b9cceae427a0ce3a0c2b12895b94e5e6af))

## [0.8.19](https://github.com/sympozium-ai/sympozium/compare/v0.8.18...v0.8.19) (2026-04-07)


### Features

* **providers:** add Unsloth as a supported local LLM provider ([9c246c1](https://github.com/sympozium-ai/sympozium/commit/9c246c13ba8947b4fe026836e764786b43329126))
* **web:** improve sidebar hierarchy, breadcrumbs, and detail page UX ([0a622d1](https://github.com/sympozium-ai/sympozium/commit/0a622d176c0ee0ad536273d5eb61c277a5e778d1))


### Bug Fixes

* **personas:** harden platform-team prompts + propagate systemPrompt edits ([079986d](https://github.com/sympozium-ai/sympozium/commit/079986d5e8edc00cd85cf9ed4d715b36f85a589b))

## [0.8.18](https://github.com/sympozium-ai/sympozium/compare/v0.8.17...v0.8.18) (2026-04-05)


### Bug Fixes

* cascade-delete scheduled AgentRuns when their Schedule is removed ([eb1ad6a](https://github.com/sympozium-ai/sympozium/commit/eb1ad6af113686ae5b77c5d3b28c4ba9a913aabb))
* scheduler picks next free run-number suffix to avoid ghost runs ([205829a](https://github.com/sympozium-ai/sympozium/commit/205829a2c1525d2b2cf5fbdb09829b254790f601))

## [0.8.17](https://github.com/sympozium-ai/sympozium/compare/v0.8.16...v0.8.17) (2026-04-05)


### Features

* **makefile:** add ux-tests-serve target for running Cypress against sympozium serve ([e9c3202](https://github.com/sympozium-ai/sympozium/commit/e9c3202d98105eff3d1b7d6008b9b4f7cd7a4d2e))


### Bug Fixes

* prevent reconcile race from overriding Succeeded AgentRuns as Failed ([d681a33](https://github.com/sympozium-ai/sympozium/commit/d681a3359f1d64ec2d8755402c0abe3849d96e8a))

## [0.8.16](https://github.com/sympozium-ai/sympozium/compare/v0.8.15...v0.8.16) (2026-04-04)


### Features

* recover qwen-native tool_calls from reasoning_content ([f807de1](https://github.com/sympozium-ai/sympozium/commit/f807de172243672997d25c3cd311740b34396fcb))

## [0.8.15](https://github.com/sympozium-ai/sympozium/compare/v0.8.14...v0.8.15) (2026-04-04)


### Bug Fixes

* surface reasoning-model responses when terminal turn is empty ([045f7d7](https://github.com/sympozium-ai/sympozium/commit/045f7d74a2f95b5ebab7eba392c6d4441734368b))

## [0.8.14](https://github.com/sympozium-ai/sympozium/compare/v0.8.13...v0.8.14) (2026-04-04)


### Bug Fixes

* skip Helm CreateNamespace when sympozium-system already exists ([e40b157](https://github.com/sympozium-ai/sympozium/commit/e40b157a238de6b91cd8f0e0e18c771eb66e5a0d))

## [0.8.13](https://github.com/sympozium-ai/sympozium/compare/v0.8.12...v0.8.13) (2026-04-04)


### Miscellaneous Chores

* release 0.8.13 ([8a6fa7b](https://github.com/sympozium-ai/sympozium/commit/8a6fa7b870da36f0df6ab0bcccaeda6b1f04fec4))

## [0.8.12](https://github.com/sympozium-ai/sympozium/compare/v0.8.11...v0.8.12) (2026-04-04)


### Bug Fixes

* publish TopicAgentRunFailed from controller so web proxy unblocks on failure ([b98841f](https://github.com/sympozium-ai/sympozium/commit/b98841fe441a3c3f478640963c270fd7ed31dd85))

## [0.8.11](https://github.com/sympozium-ai/sympozium/compare/v0.8.10...v0.8.11) (2026-04-04)


### Features

* add Cypress UX tests for instance creation and persona packs ([2ffb502](https://github.com/sympozium-ai/sympozium/commit/2ffb5026b82b116ab027c09bed58be9b9a02e8f1))
* add Cypress UX tests for instance creation and persona packs ([55e5590](https://github.com/sympozium-ai/sympozium/commit/55e5590af21dbea24e594ec7437052cc89ded4dc))
* add tool-call circuit breaker and configurable run timeout ([b5a3b94](https://github.com/sympozium-ai/sympozium/commit/b5a3b94cefeb6c7cf68a1c6f90181a2f45f28344))
* expose run timeout in web UI and CLI TUI ([3bca472](https://github.com/sympozium-ai/sympozium/commit/3bca472642dcf85df6a4f6d0f242f2ed08e3553e))


### Bug Fixes

* resolve integration test hang and flaky secret-not-found error ([2fb431f](https://github.com/sympozium-ai/sympozium/commit/2fb431f99b42e14f6f123dbf6f62229ea3a06db0))
* use sentinel value for run timeout Select to avoid Radix crash ([1553b75](https://github.com/sympozium-ai/sympozium/commit/1553b75912c1ed4037bd622de09abeaed57f290d))

## [0.8.10](https://github.com/sympozium-ai/sympozium/compare/v0.8.9...v0.8.10) (2026-04-04)


### Bug Fixes

* remove conflicting namespace pre-creation in helm install ([9930ba4](https://github.com/sympozium-ai/sympozium/commit/9930ba4497989fa40d2461e9bef7039586c67aa0))

## [0.8.9](https://github.com/sympozium-ai/sympozium/compare/v0.8.8...v0.8.9) (2026-04-02)


### Bug Fixes

* auto-store task/response in memory server after each agent run ([8f475fb](https://github.com/sympozium-ai/sympozium/commit/8f475fbc2bf600ca7fad12394e7c417dd63e2509))
* guard stale Job-not-found reconcile during postRun transition ([8d2ff41](https://github.com/sympozium-ai/sympozium/commit/8d2ff41972acb551a9aabc13cc02c1807ca50560))

## [0.8.8](https://github.com/sympozium-ai/sympozium/compare/v0.8.7...v0.8.8) (2026-04-01)


### Features

* reworked memory implementation ([81fdd0c](https://github.com/sympozium-ai/sympozium/commit/81fdd0c83725dc068bc869f01b5d1af5c421c282))


### Bug Fixes

* add missing observability-mcp-team persona pack to Helm chart ([fc0105c](https://github.com/sympozium-ai/sympozium/commit/fc0105c0d243bb0adc58680e29a4827b7aad88bd))

## [0.8.7](https://github.com/sympozium-ai/sympozium/compare/v0.8.6...v0.8.7) (2026-03-31)


### Bug Fixes

* stop Helm template from overriding node-probe host auto-detection ([4f0e5f4](https://github.com/sympozium-ai/sympozium/commit/4f0e5f41217d5ec9bf165dda7796be0df3fd307d))

## [0.8.6](https://github.com/sympozium-ai/sympozium/compare/v0.8.5...v0.8.6) (2026-03-31)


### Bug Fixes

* create namespace before Helm config init to fix fresh installs ([e49fa50](https://github.com/sympozium-ai/sympozium/commit/e49fa50f26604688a1dcbba6a3d06543b0442ea8))

## [0.8.5](https://github.com/sympozium-ai/sympozium/compare/v0.8.4...v0.8.5) (2026-03-31)


### Bug Fixes

* remove explicit host from node-probe targets to restore auto-detection ([f91229a](https://github.com/sympozium-ai/sympozium/commit/f91229afa5ba5ad0674ba6c9b202932b2a869f3f))

## [0.8.4](https://github.com/sympozium-ai/sympozium/compare/v0.8.3...v0.8.4) (2026-03-31)


### Bug Fixes

* strip directory prefix from CRD names when writing to temp dir ([1906327](https://github.com/sympozium-ai/sympozium/commit/1906327b3abd32dc887f5a09c98eada9e0fb09b6))

## [0.8.3](https://github.com/sympozium-ai/sympozium/compare/v0.8.2...v0.8.3) (2026-03-31)


### Bug Fixes

* add metrics.k8s.io RBAC to config/rbac/role.yaml for sympozium install ([0c1a51c](https://github.com/sympozium-ai/sympozium/commit/0c1a51c8d11354aa5e2df694e8557c120b474857))

## [0.8.2](https://github.com/sympozium-ai/sympozium/compare/v0.8.1...v0.8.2) (2026-03-31)


### Bug Fixes

* resolve remaining TypeScript index signature errors in yaml-panel ([8cea011](https://github.com/sympozium-ai/sympozium/commit/8cea0119064536a30ba8a1a15d119af73c9380a9))

## [0.8.1](https://github.com/sympozium-ai/sympozium/compare/v0.8.0...v0.8.1) (2026-03-31)


### Bug Fixes

* fail AgentRun when skill RBAC creation fails instead of silently continuing ([99ddb4d](https://github.com/sympozium-ai/sympozium/commit/99ddb4d698bedd758c7d5512e6da354dad5db754))
* resolve TypeScript index signature errors in yaml-panel ([4a576a1](https://github.com/sympozium-ai/sympozium/commit/4a576a1b8db3f77c7ee6cb610b08f212b3ab9cd0))

## [0.8.0](https://github.com/sympozium-ai/sympozium/compare/v0.7.0...v0.8.0) (2026-03-30)


### Features

* lifecycle hooks — preRun and postRun containers for agent runs ([a29a8c9](https://github.com/sympozium-ai/sympozium/commit/a29a8c99a67287f063f2b1398b9e499b57e51d35))
* lifecycle hooks — preRun and postRun containers for agent runs ([#67](https://github.com/sympozium-ai/sympozium/issues/67)) ([46250af](https://github.com/sympozium-ai/sympozium/commit/46250afb1e379378e0a82d1d450a811f0a2181dc))


### Bug Fixes

* update API key retrieval to use header instead of query parameter ([e320e8d](https://github.com/sympozium-ai/sympozium/commit/e320e8d8361107acf30af4d35b9df2cd866c0cda))
* update API key retrieval to use header instead of query parameter ([ba6281a](https://github.com/sympozium-ai/sympozium/commit/ba6281a546a18f2b42193c5203049b08eb4eb983))
* update RBAC rules to include metrics.k8s.io permissions for skill sidecars ([cad5b4a](https://github.com/sympozium-ai/sympozium/commit/cad5b4a7eef051efd239604e472be905b4d28d21))
* update RBAC rules to include metrics.k8s.io permissions for skill sidecars ([3f90317](https://github.com/sympozium-ai/sympozium/commit/3f90317d172cc8d43a0d37b952196f48b3f73fe5))

## [0.7.0](https://github.com/sympozium-ai/sympozium/compare/v0.6.1...v0.7.0) (2026-03-29)


### Features

* add apiKey support for provider models fetching ([369fab3](https://github.com/sympozium-ai/sympozium/commit/369fab35e02dd9a5effadb9ce68ccd39d14f6b0e))
* add apiKey support for provider models fetching ([fb4bb53](https://github.com/sympozium-ai/sympozium/commit/fb4bb53b302ff0e11b176e9dba2e19a8856d2295))


### Bug Fixes

* AgentRun status concurrency update ([87dbb22](https://github.com/sympozium-ai/sympozium/commit/87dbb2226b22de4106d7c7c90fb77101c4217f38))
* prevent apiserver image build timeout on multi-arch builds ([830329d](https://github.com/sympozium-ai/sympozium/commit/830329d94295f04a496594ff494100a9e48fd1e1)), closes [#60](https://github.com/sympozium-ai/sympozium/issues/60)

## [0.6.1](https://github.com/sympozium-ai/sympozium/compare/v0.6.0...v0.6.1) (2026-03-28)


### Bug Fixes

* chain release workflow from release-please via workflow_call ([22c9e1e](https://github.com/sympozium-ai/sympozium/commit/22c9e1e9a17a52907e6c3424855bc82ce1cfb5b1))

## [0.6.0](https://github.com/sympozium-ai/sympozium/compare/v0.5.8...v0.6.0) (2026-03-28)


### Features

* Add image pull secret propagation for agent run container ([51858a3](https://github.com/sympozium-ai/sympozium/commit/51858a3686d9a7593eaf20def93e77ad726825b6))
* Add image pull secret propagation for agentrun sidecar container ([d5f4852](https://github.com/sympozium-ai/sympozium/commit/d5f4852515320378b2a36a31a7ff3e6e083f0f9f))
* add RBAC permissions for metrics access on pods and nodes ([013b02e](https://github.com/sympozium-ai/sympozium/commit/013b02eede3918664eed3f0018d93e8d66782be8))
* add RBAC permissions for metrics access on pods and nodes ([d94ed79](https://github.com/sympozium-ai/sympozium/commit/d94ed79da573375e22186ebc8e6d5c264e56549d))
