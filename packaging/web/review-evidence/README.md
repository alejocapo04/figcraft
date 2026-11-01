# Native optional file-provider evidence

Source: `67e4ba66f05375b702c77a74e5e837bc64b5e748`. Workflow: `b8f71efc81ba535b3ae8c49d543d538ce121c973`.

The synthetic local-history entry deliberately has no corresponding device file, so its existing missing-file warning is expected. These captures do not validate opening a local file.

Rendered with the repository native offscreen renderer and pinned fonts. This is not browser/backend end-to-end evidence. No server, credentials or private files were used.

Run: https://github.com/alejocapo04/figcraft/actions/runs/41281018434

- `local.png`: provider absent (default).
- `provider.png`: synthetic provider registered; device history remains separate.

The evidence lives on this review-only branch and is excluded from the feature PR. See provenance.json for input and image hashes.
