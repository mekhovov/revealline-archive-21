# RevealLine archive 21

Retain the exact original v0.60.7 release while newer editions become current. This repository contains small original metadata and bounded publication tools. Hosted preparation fetches the published original ZIP, verifies every member against its original manifest, and deletes the temporary ZIP. It never rebuilds the game or commits expanded payload files.

The expected complete site is **698 files / 313,213,410 bytes**, leaving **486,786,590 bytes** under the unchanged **800,000,000-byte** cap. All 690 original site members are retained. The root links directly to v0.60.7; Release explorer uses the established immediate redirect plus visible fallback to the main live catalog. Metadata, source qualification, annotated tag and frozen source stay unchanged. See `source-lock.json` and `input-authority.json`. An authored inventory is an expectation, not evidence of deployment.

## Review and publication

Seed main with a README only, no workflow. Adopt the reviewed files on `codex/retain-v0607` against that actual seed, review hunks and a normal PR, then merge its exact reviewed head. Configure Actions Pages and a main-only `github-pages` environment before merging. Both workflow jobs are main-only. Exactly one main push starts deployment. Manual dispatch exists only for a necessary recorded retry, never a duplicate running deployment. The inherited workflow does not advertise PR CI or perform PR deployment.

The workflow checks out the pinned source only for the unchanged bounded ZIP extractor and corruption tests. It checks the annotated tag, original source/metadata/qualification, every extracted member and full final inventory. Preserve contents-read and deploy-only Pages/id-token permissions, the 3 GiB runner free-space floor, 800 MB/20,000-file limits and original failure receipts.

Run `python3 -B -m unittest discover -s tools -p 'test_*.py' -v` for small offline fixtures, and the pinned extractor's `test_extract_current.py` cohort separately. Those are synthetic checks, not a payload build or public acceptance. Never run full preparation on a nearly full local disk.

After successful hosted deployment, retain actual source/tree/run/deployment/status and small receipt descriptors. Audit every expected public file with fresh before/after authority checks. Separately exercise retained v0.60.7 title, actual flight, Pause/Resume and Release explorer → current main catalog → Back. Only then may the main publisher admit this archive. There are no predecessor rows on this new origin; do not invent a preservation claim. Archive-origin storage does not migrate main-origin saves. No offline, physical-device, BFCache or whole P03/P05/P18 acceptance follows.

Future appends must preserve all canonical rows and fit the same cap. Never overwrite original release assets, reuse stale admission evidence, repurpose existing URLs or raise the cap.
