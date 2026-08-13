# GameDailyAgent Provider Artifacts

This public repository contains immutable release assets used by GameDailyAgent to install Provider Adapters and task-specific resources.

The GameDailyAgent source repository remains private. Artifact identity, byte size, SHA-256, required files and download URLs are defined by its `configs/provider-artifacts.json` manifest.

Published assets are never replaced in place. Any content change receives a new versioned filename and manifest entry.

The production update catalog is `provider-catalog-v1.signed.json`. Its payload is signed offline with
the GameDailyAgent Ed25519 release identity; GDA embeds only the corresponding public key.
