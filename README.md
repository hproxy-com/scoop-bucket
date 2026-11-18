# HProxy for Scoop

The `hproxy` command on Windows: check proxies, list free ones, look up IPs, connect through a proxy, and give AI
assistants the same tools as an MCP server (`hproxy mcp`).

```powershell
scoop bucket add hproxy https://github.com/hproxy-com/scoop-bucket
scoop install hproxy/hproxy
hproxy --help
```

Every version is built in public from source (https://github.com/hproxy-com/proxy-all-in-one-tool/releases) and the manifest names the
SHA-256 sums of that release. Upgrade with `scoop update hproxy`.

More: https://hproxy.com/tools/ai · support around the clock: https://hproxy.com/contact
