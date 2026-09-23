# Agent Guide for the Knowledge Base Navigation Layer

Use these files as a navigation map. Do not treat them as a replacement for the underlying concept files.

Before answering a marketing question:

1. Read `AGENTS.md`.
2. Read `kb/kb-entrypoints.md`.
3. Use `kb/kb-manifest.json` to identify candidate files by tag, type, and status.
4. To find a file's neighbours, use its own `## Invokes` (what it points to) and `## Referenced by` (what points to it) sections -- both are already in the file, no separate lookup needed. `kb/kb-graph.json` carries the same data but as a large JSON file, realistic to query only if you have code execution; prefer the in-file sections otherwise.
5. Open the actual Markdown files before using a concept.
6. If the map and the concept file disagree, trust the concept file and report the map issue.
7. Treat draft and boundary-marked files with appropriate caution.

The navigation files help you find likely sources. They are not evidence by themselves.
