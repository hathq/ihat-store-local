# Local placement

Package: `@hathq/ihat-store-local`, immutable development version **0.10.0**.

`localStore(rpc, options)` composes the source adapter with the common store core. The injected owner RPC reads the configured local catalog; this package performs no filesystem lookup, network fallback or installation.

Local operation needs only an explicitly configured local source whose signed metadata and artifacts are already present. Missing online placement must not block this path, or unrelated Subject/Resolution/Operation scenes.

No semantic, control, installation, credential or renderer authority is transferred
to iHat. Acceptance and remaining work are recorded in
`docs/architecture/ihat-online-architecture.json` at the Wonderland root.
