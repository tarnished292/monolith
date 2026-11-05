# Monolith

**A Rust-powered music engine for modern applications.**

Monolith is a high-performance, modular music engine built in Rust. It provides the underlying infrastructure for music discovery, metadata processing, audio resolution, streaming, and playback.

Designed as an independent and reusable library, Monolith separates music functionality from application interfaces, making it suitable for integration across mobile, desktop, and other platforms.

> Music first. Files second.

## Core Capabilities

Monolith focuses on the essential systems required to deliver a complete music experience.

- **Music Discovery** — Search and retrieve music from supported providers.
- **Metadata Processing** — Extract, normalize, and manage track, artist, album, and artwork information.
- **Audio Resolution** — Identify playable audio sources and select suitable audio formats.
- **Audio Streaming** — Deliver audio efficiently with support for HTTP range requests and seeking.
- **Lyrics Integration** — Retrieve and associate lyrics with music.
- **Provider Integration** — Integrate multiple music sources through a consistent interface.
- **Playback Infrastructure** — Provide the underlying capabilities required by music playback applications.
- **Data Normalization** — Maintain consistent models across different providers.

## Built for Integration

Monolith is designed to operate independently of the application consuming it.

Its functionality can be integrated into different environments through appropriate interfaces, including:

- Native Rust applications
- Mobile applications
- Desktop applications
- HTTP-based application backends

The engine does not impose a particular UI framework, application architecture, or presentation layer.

## Engineering Principles

**Performance**

Built with Rust and asynchronous execution to handle network operations and audio delivery efficiently.

**Modularity**

Music providers and individual capabilities should remain independently maintainable and extensible.

**Consistency**

Normalize provider-specific data into predictable, application-friendly models.

**Reliability**

Handle network failures, provider differences, format selection, and streaming errors explicitly.

**Portability**

Keep the core independent of platform-specific application concerns.

**Extensibility**

Provide a foundation that can evolve alongside new providers, integrations, and music-related capabilities.

## Technology

- Rust
- Tokio
- Reqwest
- Serde

## Development Status

Monolith is under active development. Its public APIs, provider integrations, and capabilities are subject to change as the engine evolves.

## License

MIT License. See [LICENSE](LICENSE) for details.

---

**Monolith — Music first. Files second.**