# HanaMesh plugins · Agent 0.2.6 cleanup candidate

This candidate combines normal Usage 0.3.0-rc.14 with normal Core 0.3.25. Official Codex remote plugins use their native remote_plugin_id across versions, including connectors. Plugin calls during runtime preparation retain minimal local metadata and are processed when ready; upload requires website consent and device binding.

Usage source a70e65885190fcc927cf1e94d9188fd26baed50f; normal Usage SHA256 11cd745b2a6ed9398cc8fcf9a603079210807dff39d4fd0a036e4ca414da6ab1; Core SHA256 6de09a6c65bc894ecb4a89482b8ca6fa184274ef9b98f5d57fe7817c56e2db12; payload SHA256 decf10eb52f8da50a6ea16a3bee8f9cefd53011bf8320c11d38cc54ca8f917fe. Payload bytes and execute modes match these normal inputs; runtime/core/package.json is the minimal metadata projection.

Author candidate, pending independent R2 review. No publication, main merge, deployment or Host switch. No Node binary/archive is bundled. See plugins/hanamesh/suite-receipt.json.
