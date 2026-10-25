# HanaMesh plugins

Official single-plugin marketplace for Claude Code and Codex. The `hanamesh` plugin is version 0.1.2 and contains the reviewed Usage 0.3.0-rc.5 + Core 0.3.20 agent payload.

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

The unchanged [suite receipt](plugins/hanamesh/suite-receipt.json) records all 66 payload files, Usage source `3a504bc40de32e30bb914d675562ac62e1dae8c5`, and Core tarball SHA256 `1a51ed245d2c9a5ad6f15ffdeea5cade03aa7139b4772576529d74fb4bc4d016`. Payload SHA256: `d2270d783e3d57bc31edd67431197117de976891b55ce74131ea6313d5ba186f`.

Upstream source: [HanaMesh Usage](https://github.com/yzsnstotz/hanamesh-usage). License: MIT; the embedded Core license is retained.
