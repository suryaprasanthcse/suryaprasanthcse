### Hi, I'm Surya

I test concurrency and correctness in graph databases and agent-memory layers. I find the races that only show up when many workers write at once, prove each one with a replayable test, and send the fix upstream.

**Open to remote contract work:** concurrency audits, regression test suites and upstream fixes. [Portfolio](https://suryaprasanthcse.netlify.app)

#### Upstream work

| Project | What | Status |
|---|---|---|
| Graphiti | `remove_episode` racing `add_episode` loses the new fact: [issue #2159](https://github.com/getzep/graphiti/issues/2159), fix and regression test in [PR #2177](https://github.com/getzep/graphiti/pull/2177) | PR open, in review |
| Omnigraph | Wrong refusal type when a conditional write loses a race: [issue #1424](https://github.com/ModernRelay/omnigraph/issues/1424) | Fixed by the maintainers in [#1426](https://github.com/ModernRelay/omnigraph/pull/1426) |
| Graphiti | FalkorDB lost writes on kill under the default Compose setup: measured in [#2117](https://github.com/getzep/graphiti/issues/2117) | Fix [PR #2118](https://github.com/getzep/graphiti/pull/2118) open, cites the measurement |
| FalkorDB | Filters pushed past `LIMIT`/`SKIP` in a `WITH` clause: [issue #3694](https://github.com/FalkorDB/FalkorDB/issues/3694) | My fix [PR #3699](https://github.com/FalkorDB/FalkorDB/pull/3699) open |
| FalkorDB | Fulltext queries answer from an index still under construction: [issue #3931](https://github.com/FalkorDB/FalkorDB/issues/3931) | Open |

#### Projects

- **[Witnessmark](https://github.com/suryaprasanthcse/witnessmark)**: checks seven concurrency and temporal invariants on Graphiti, Cognee, Omnigraph, FalkorDB and Neo4j. Every verdict has a replayable witness, and every report regenerates byte for byte.
- **[GNOMON](https://github.com/suryaprasanthcse/gnomon)**: an event-sourced runtime for AI agents built inside FalkorDB, with atomic task leases, bitemporal memory and branching.
- **[Kensho](https://github.com/suryaprasanthcse/kensho)**: deterministic validation gates and headless render tests for model-written scenes and generated 3D assets.

#### Awards

- 1st place, Game Tech Track, Cambridge × Arcade AI Hackathon ([GOLEM](https://github.com/suryaprasanthcse/GOLEM-HY3D-Orchestrator))
- 3rd place, HackMatrix 2026 ([SYNAPSE-3D](https://github.com/suryaprasanthcse/SYNAPSE-3D-AA32))

Python · Cypher · Neo4j · FalkorDB · Docker · TypeScript · C# / Unity
