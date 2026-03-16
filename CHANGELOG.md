# Changelog

## 0.1.0 (2026-03-15)

- Initial release
- Pod base class with 6-phase boot sequence
- Ed25519 identity generation via browsermesh-primitives
- BroadcastChannel peer discovery
- Pod kind detection (window, iframe, worker, service-worker, etc.)
- Runtime capability detection (messaging, network, storage, compute)
- Wire protocol message factories (hello, hello-ack, goodbye, message, rpc-request, rpc-response)
- InjectedPod subclass for Chrome extension / bookmarklet injection
- Runtime convenience functions: installPodRuntime, createRuntime, createClient, createServer
