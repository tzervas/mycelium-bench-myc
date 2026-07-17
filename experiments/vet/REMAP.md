# Remap Manifest — mycelium-bench → bench

_DN-109 §5.2 provenance ledger. Guarantee: **Declared** — this records proposed/performed structural and idiom choices; it does not certify them (no guarantee-tag upgrade from the manifest's existence alone, VR-5). Rendered from `remap` in `summary.json` — this file is a pure projection, never a second source of truth._

## Nodules (10)

| Target nodule | Operation | Safety | API surface changed | Identity neutral | Sources | Rationale |
|---|---|---|---|---|---|---|
| `bench.backend` | Keep | Safe | false | true | `/root/git/isolated/mycelium/crates/mycelium-bench/src/backend.rs` | structure-preserving 1:1 (DN-109 §5.3-B v0 default: every emitted nodule keeps its source file's mod-tree position, no restructuring proposed) |
| `bench.bin.bench` | Keep | Safe | false | true | `/root/git/isolated/mycelium/crates/mycelium-bench/src/bin/bench.rs` | structure-preserving 1:1 (DN-109 §5.3-B v0 default: every emitted nodule keeps its source file's mod-tree position, no restructuring proposed) |
| `bench.corpus` | Keep | Safe | false | true | `/root/git/isolated/mycelium/crates/mycelium-bench/src/corpus.rs` | structure-preserving 1:1 (DN-109 §5.3-B v0 default: every emitted nodule keeps its source file's mod-tree position, no restructuring proposed) |
| `bench` | Keep | Safe | false | true | `/root/git/isolated/mycelium/crates/mycelium-bench/src/lib.rs` | structure-preserving 1:1 (DN-109 §5.3-B v0 default: every emitted nodule keeps its source file's mod-tree position, no restructuring proposed) |
| `bench.llm` | Keep | Safe | false | true | `/root/git/isolated/mycelium/crates/mycelium-bench/src/llm.rs` | structure-preserving 1:1 (DN-109 §5.3-B v0 default: every emitted nodule keeps its source file's mod-tree position, no restructuring proposed) |
| `bench.measure` | Keep | Safe | false | true | `/root/git/isolated/mycelium/crates/mycelium-bench/src/measure.rs` | structure-preserving 1:1 (DN-109 §5.3-B v0 default: every emitted nodule keeps its source file's mod-tree position, no restructuring proposed) |
| `bench.report` | Keep | Safe | false | true | `/root/git/isolated/mycelium/crates/mycelium-bench/src/report.rs` | structure-preserving 1:1 (DN-109 §5.3-B v0 default: every emitted nodule keeps its source file's mod-tree position, no restructuring proposed) |
| `bench.scaling` | Keep | Safe | false | true | `/root/git/isolated/mycelium/crates/mycelium-bench/src/scaling.rs` | structure-preserving 1:1 (DN-109 §5.3-B v0 default: every emitted nodule keeps its source file's mod-tree position, no restructuring proposed) |
| `bench.timing` | Keep | Safe | false | true | `/root/git/isolated/mycelium/crates/mycelium-bench/src/timing.rs` | structure-preserving 1:1 (DN-109 §5.3-B v0 default: every emitted nodule keeps its source file's mod-tree position, no restructuring proposed) |
| `bench.verdict` | Keep | Safe | false | true | `/root/git/isolated/mycelium/crates/mycelium-bench/src/verdict.rs` | structure-preserving 1:1 (DN-109 §5.3-B v0 default: every emitted nodule keeps its source file's mod-tree position, no restructuring proposed) |

## Idiom choices (0)

_(none in this run — v0 Mechanical-only auto-fire with no located idiom-choice instrumentation yet; see DN-109 §7-e and this module's doc comment)_
