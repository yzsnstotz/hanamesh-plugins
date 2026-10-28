# HanaMesh plugins · Agent 0.2.2 candidate

This review candidate materializes Usage 0.3.0-rc.10 and the frozen Core 0.3.25 normal artifact. It repairs an abandoned PREPARING state after validated Node publication: only a free preparation lock allows reconciliation; active preparation remains visible and hooks stay paused. Explicit local close remains closed, and calls from the preparation window are never backfilled.

The public main marketplace remains on its previous release. No Node archive or binary is committed here; the original recipe, official origin and startup/preparation budgets remain unchanged. Website agreement and device binding are still required before upload. Native Disable stops execution and does not prove local clearing or remote withdrawal. MCP exposes only readonly hanamesh_status; DSH keeps its existing consent flow.

```text
Claude Code: /plugin marketplace add yzsnstotz/hanamesh-plugins
Claude Code: /plugin install hanamesh@hanamesh
Codex: codex plugin marketplace add yzsnstotz/hanamesh-plugins
Codex: codex plugin add hanamesh@hanamesh
```

The [suite receipt](plugins/hanamesh/suite-receipt.json) anchors 71 payload files, Usage source e0ef289d88b98e869b9d792534b299766b1fc091, normal Usage SHA 870c909508af7f3af02156e366a40b7f7962e40179db7ada637bd326776770ba, Core SHA 391a839eda529f443e1329335a03ca67376ba28e0b3df2b1989fd5428d23e5d5, and payload SHA f5b7ce80a9195ecab37e2550ba7b46afadb84874fae2793becf433de7a607c4b. Seventy files and executable modes match normal inputs; runtime/core/package.json is the validated minimal projection of Core metadata.

The formal profile remains api.hanamesh.com / market.hanamesh.com. Local/staging tests use an explicit complete loopback pair. The first fresh native cold acceptance failed at official TLS connection with zero bytes; it is retained as FAIL. A later independent cold acceptance after IPv4/IPv6 connectivity verification is tracked separately in the C delivery evidence. This README does not claim that all cold starts or networks pass. Full real-model/UI, website integration, x64 execution, independent review and professional privacy-copy review remain separate gates. No npm publication, deployment or product-main merge is performed here.

Upstream: [HanaMesh Usage](https://github.com/yzsnstotz/hanamesh-usage). MIT; embedded Core license retained.
