# Brioche curriculum ownership

This repository owns French author lessons, original curriculum artwork, examples, and immutable release records. Product and learning framework business code belong in Brioche and Chef respectively. Do not copy private recordings, account data, voice credentials or recovery material here.

Previously published lesson revisions remain immutable. Change content by adding a new revision and release; do not rewrite historic source files. `SOURCE.json` records the original extraction. Keep LF to preserve image hashes.

CI uses a fixed Chef revision to validate exact lesson revisions referenced by the current release. This offline check validates structure, placement and grading; it does not establish media registration, actual audio quality or production publication. Direct publication is authorized by the owner, but retain real source/permission validation and immutable audit, never forge human listening declarations.

Consumers pin this repository as a submodule. Push validated course changes here before updating product pins; never use floating production updates.
