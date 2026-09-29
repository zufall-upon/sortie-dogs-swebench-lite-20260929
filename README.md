# Sortie-dogs v0.12.24 — SWE-bench Lite test evidence

**170/300 resolved (56.67%)**, pass@1 on the 300-instance Lite **test** split.
Nine empty predictions are included in the denominator. The other 291 instances
have official evaluation logs, and none has an evaluation error.

- [System source and logo](https://github.com/zufall-upon/Sortie-dogs)
- [Technical report, setup, model roles, costs and limitations](https://github.com/zufall-upon/Sortie-dogs/blob/main/docs/benchmarks/swebench-lite-v01224-test300-2026-09-29.md)
- [Leaderboard submission](https://github.com/SWE-bench/experiments/tree/main/evaluation/lite/20260929_sortie-dogs-luna-max) (subject to maintainer review)

`all_preds.jsonl` contains the single frozen prediction per instance. `logs/`
contains the packaged official per-instance patch, report and compressed test
output where available; `trajs/` contains the visible text and tool events
exported from the original inference-time OpenCode sessions. No hidden
reasoning or credential tables are included. The original session databases
and replay files are retained separately, not uploaded here.

Candidate archive SHA-256: `3e4968ae8c72768347d8d37411eb7ad2e9213110e126b835de57a7a4e5b27823`.
Frozen 300-case prediction SHA-256 (original campaign file):
`3fc0aac92c029ce519a269941221301090e5240c6f4199c885d237a9be5cff06`.
Single official 300-case report SHA-256 (original campaign file):
`031d2cbc26599297108e17349153fbea589394c2022a1f465325203fb8e67a6d`.
The submit packager independently re-derived 170 resolved and 9 empty
predictions; `swebench submit verify` passed on the 291 graded instances.
This is a locally evaluated submission, **not** a claim of maintainer-verified
leaderboard acceptance or a Verified/full SWE-bench score.
