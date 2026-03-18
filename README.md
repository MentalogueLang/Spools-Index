# Spools Index

This repository is the Suture spools registry. Each spool entry lives under
`entries/<bucket>/<name>/<version>/spool.toml`, where `<bucket>` is `a`..`z`
or `lib`.

Use the public `Spool Upload` workflow to add new entries. The recommended CLI
path is `suture publish <spool.toml>`, which posts the spool manifest to the
workflow through a GitHub issue comment trigger with rate limiting.
