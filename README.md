# HanaMesh plugins · Agent 0.2.6 cleanup candidate

This candidate combines normal Usage 0.3.0-rc.14 with normal Core 0.3.25. Official Codex remote plugins use their native remote_plugin_id across versions, including connectors. Plugin calls during runtime preparation retain minimal local metadata and are processed when ready; upload requires website consent and device binding.

Usage source db2eb6af93a129327622eabc9c25e962241310ac; normal Usage SHA256 4d519791fa517f39c7f4efa2cffd603e17124011083b3a3bd533660624db5517; Core SHA256 6de09a6c65bc894ecb4a89482b8ca6fa184274ef9b98f5d57fe7817c56e2db12; payload SHA256 5a14b82091499e9f48b1df677725c96fabb112479e7013612069c7ef6de9dd9a. Payload bytes and execute modes match these normal inputs; runtime/core/package.json is the minimal metadata projection.

Author candidate, pending independent R2 review. No publication, main merge, deployment or Host switch. No Node binary/archive is bundled. See plugins/hanamesh/suite-receipt.json.
