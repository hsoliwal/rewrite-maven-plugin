<!-- SPDX-License-Identifier: Apache-2.0 -->
# Repository agent policy

## Priority 0 — full-history superset-merge custody and last-checked rule (2026-11-18)

Every accepted fork evolves as a **backward-compatible optimized API/behavior superset** of applicable historical upstream and fork capabilities. Source/API/ABI, tests, platform/native lifecycle, formats, earlier fixes and measured optimizations must not be silently lost. Evaluate multiple candidate algorithms, old branches and PRs, and choose the best *proven* implementation using correctness, allocation, latency, throughput, concurrency and license compatibility; grow APIs additively. Before any merge, inspect Git ancestry back to the earliest reachable root across all relevant heads/tags, merged/closed/reverted PRs, both merge parents, renames/deletions and previously rejected bad commits; never rebase `develop`. Record per-ref last-checked date, exact SHA, scan scope/oldest ancestor, PR/branch coverage, previous verified SHA and findings in the canonical Synexia checkpoint ledger. A HEAD snapshot is only PARTIAL/PENDING. Use the established Synexia Maven/OpenRewrite recipes, exact-source history-loss and target compiler/behavior/native gates in accordance with each repository role. Prefer Apache-2.0 for **new separable first-party** code, retain applicable upstream/donor licenses and NOTICE, and never treat LLM-assisted atomization/patternization as automatic relicensing. Canonical instructions and explicitly PENDING 236-repo inventory: [com.synexia PR #18764](https://github.com/hsoliwal/com.synexia/pull/18764).



## Superset merge and history-audit rule (2026-11-18)

Read [.github/MERGE_RULE.md](.github/MERGE_RULE.md) before changing an existing implementation or integrating any branch or PR.
Preserve the supported additive API/behavior superset and select implementations by correctness, predictability, measured performance, then elegance.
Audit all reachable history back to every root, all branches/tags and all PR states for lost code or regressions; preserve append-only history.
Record actual UTC coverage and remaining work in [.github/HISTORY_AUDIT.tsv](.github/HISTORY_AUDIT.tsv); policy installation is not a completed source-history audit.
Prefer verified Apache-2.0 sources and independent implementations while preserving all existing third-party rights; LLM rewriting does not remove license obligations.
Detailed private recipe/proof records remain in canonical Synexia; the compact local policy and checkpoint make the rule discoverable here.
<!-- MERGE-SUPERSET-HISTORY-20261118-2 -->

# Repository agent policy

## Owner directive: best-of-best additive convergence and full-history checkpoint (2026-11-18)

Inspect all accessible Git history to its roots, all branches/tags and paginated open/closed/merged/rejected PRs with their head/merge refs before replacing code. Compare actual pre/post source and public API/behavior/test inventories; a merged PR/ancestry alone is not proof of surviving functionality. Identify and recover lost verified optimizations, API extensions and tests via the canonical Synexia Maven/OpenRewrite recipe, not destructive rebase.

Converge the strongest compatible correct algorithms into an additive superset; retain original type identity, source/binary/reflection/serialization contracts, native/resource guarantees, regressions and build/test gates. Reusable recipes and evidence belong to `hsoliwal/com.synexia`; this repository receives only appropriate product code and tests.

Prefer Apache-2.0 for separately original and legally eligible new work; retain all upstream GPL/EPL/Apache/LLVM exception or other per-file licensing and NOTICE as applicable. A new, independently expressed implementation of an abstract algorithm may be used when permitted; LLM paraphrase cannot erase another author's code copyright or patent rights.

Write exact last-check date, repo/default SHA, root/ref/PR coverage, delivered-source loss findings and test status to `hsoliwal/com.synexia/docs/M3-SCALE/invariants/SYNEXIA-HISTORY-REVIEW-LAST-CHECKED.tsv`. Until complete, mark PARTIAL; do not claim full-history audit from a sampled head.
