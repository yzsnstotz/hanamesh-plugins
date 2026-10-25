# HanaMesh plugins

Official single-plugin marketplace for Claude Code and Codex. The `hanamesh` plugin is version 0.1.3 and contains the reviewed Usage 0.3.0-rc.6 + Core 0.3.21 agent payload.

Claude Code, inside a session:

```text
/plugin marketplace add yzsnstotz/hanamesh-plugins
/plugin install hanamesh@hanamesh
```

Codex, in a terminal:

```sh
codex plugin marketplace add yzsnstotz/hanamesh-plugins
codex plugin add hanamesh@hanamesh
```

After installation, follow the bundled [runtime and configuration instructions](plugins/hanamesh/README.md). The runtime bootstrap currently supports macOS arm64 and x64 and downloads the fixed Node 24.13.1 runtime from nodejs.org. Service and website origins must be configured explicitly. This marketplace does not enable usage recording, sign in, bind an account, or approve hooks for you. Review the hooks and complete trust and consent yourself.

The unchanged [suite receipt](plugins/hanamesh/suite-receipt.json) records all 66 payload files, Usage source `993a1312aababcbf97efd6c365705a1aa6217cb7`, and Core tarball SHA256 `4e5e3e4e2dda53ed0128d5d0295b27b4db086715beafe42e4ecb56fea4077804`. Payload SHA256: `12ec76cf1092f498fa441a8916466130268b63b1f280477da63ee77bdc0c704c`.

Upstream source: [HanaMesh Usage](https://github.com/yzsnstotz/hanamesh-usage). License: MIT; the embedded Core license is retained.
