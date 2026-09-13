# Causolith schema mirror

This repository publishes the frozen Draft 4 schema bytes used by early
Causolith workspaces. Their embedded `$id` values are historical identifiers:
changing them would alter the schema lock and invalidate references in
immutable records. A subsequent format version will use Causolith identifiers
and an explicit migration from Draft 4.

All rights reserved. No license is granted by this repository.

The raw Draft 4 schema base is:

`https://raw.githubusercontent.com/sodini-io/causolith-schema/main/schemas/0.1-draft.4/`

Validate against the checked-in `schema-lock.json` before use.
