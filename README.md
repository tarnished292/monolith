# Monolith VPN

**A from-scratch VPN implementation in Rust.**

Monolith is an experimental network security project exploring the design and implementation of a custom VPN protocol. It focuses on secure packet transport, authenticated communication, and the systems-level mechanics underlying virtual private networking.

The project is developed with an emphasis on protocol integrity, explicit security boundaries, and predictable behavior under adverse network conditions.

## Philosophy

**Security is a property of the system, not a feature added to it.**

Monolith is built around the principle that network infrastructure should be understandable at its foundations. Protocol design, cryptographic guarantees, packet handling, and operating-system integration are treated as interdependent components rather than isolated implementation details.

Complexity is introduced deliberately. Abstractions must justify their existence, protocol behavior must remain explicit, and security assumptions must be documented rather than concealed behind implementation convenience.

Cryptographic primitives will be drawn from established libraries. Custom protocol engineering is an exercise in systems design—not an attempt to reinvent cryptography.

## Security Disclaimer

Monolith is under active development and has not undergone an independent security audit. Its security properties have not been established, and it must not be used to protect sensitive communications or production traffic.

## License

See [LICENSE](LICENSE) for licensing information.