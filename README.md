# Kanban WS — Real-time Board (Vanilla Stack)

A real-time Kanban board built with **pure HTML, CSS, JavaScript, and Node.js** — no frameworks, no third-party libraries.

## Status

🚧 Scaffold. Project structure and README only.

## Why vanilla?

No `ws`, no Socket.io, no frontend frameworks. The WebSocket handshake will be implemented directly on top of Node's built-in `http` module using `crypto`. The goal is to understand the protocol (RFC 6455) rather than rely on abstraction.

## Planned

- HTTP server with static file serving
- Manual WebSocket handshake
- Server-rendered HTML fragments sent over WebSocket
- Drag-and-drop with vanilla JS
- SQLite persistence
- Reconnection logic
