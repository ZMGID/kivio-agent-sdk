# Origin

The current SDK snapshot comes from Kivio [commit 92f18f50ce20c215d224f4b062e51d2c92372c50](https://github.com/ZMGID/kivio/commit/92f18f50ce20c215d224f4b062e51d2c92372c50), which merged the SDK v2 implementation in PR #76. Access to the upstream repository may be restricted.

The SDK runtime source, examples, Rust tests, lockfiles and license were copied unchanged. The SDK retains its [GPL-3.0-or-later license](../LICENSE). The independent consumer and boundary checker come from the same snapshot. Their paths, documentation, package metadata and CI configuration are adapted for this standalone repository.

This repository started from [commit 126547462cee9bb4cde7544270e96c163a86296e](https://github.com/ZMGID/kivio/commit/126547462cee9bb4cde7544270e96c163a86296e). The existing `v0.1.0-alpha.1` tag retains that initial API. SDK v2 describes the design iteration, not a published `2.0` release. Pin a commit containing this update to use the new API.

This repository is a snapshot. Changes made here or upstream do not flow to the other repository automatically. Future synchronization requires a deliberate port.
