# Cooper Kaspian

**Systems Developer & Rust Enthusiast** based in Salem, Oregon.

I specialize in **low-level systems programming**, **reverse engineering**, and **modern systems languages** (Rust, Go, C, C#). My work focuses on understanding how software functions at a fundamental level—deconstructing compiled code to build efficient, performant utilities and exploring next-generation programming paradigms.

[**wednesday.wtf**](https://wednesday.wtf) • [**ckaspian@pm.me**](mailto:ckaspian@pm.me)

---

### 🛠️ Technical Expertise

| **Core Domain** | **Languages & Tools** |
| :--- | :--- |
| **Systems Programming** | Rust, Go, C (C99/C11), C++ |
| **Reverse Engineering** | Harmony, BepInEx, MelonLoader, x64dbg, YARA |
| **Async & Networking** | Tokio, Hyper, Protocol Buffers, gRPC, Goroutines |
| **Backend Architecture** | Service-Oriented Design, REST APIs, PostgreSQL, Transaction Management |
| **Embedded & DSP** | Assembly, FPGA, GPU optimization |
| **Development** | Linux/Windows, Git, Cargo, Go Modules, Make, CMake |

---

### 🔭 Featured Projects

#### **[Godin](https://github.com/ckaspian/Godin/tree/next)**
> *Go, Service-Oriented Architecture, PostgreSQL, Discord Integration*

A **production-grade backend service** implementing **service-oriented architecture** with dynamic handler dispatch. Designed around a CDN pattern for scalable resource management with Discord integration for guild/channel/webhook orchestration.

**Technical Highlights**:
*   **Dynamic Handler Dispatch**: Plugin-based service registration via standardized `cdn.Handler` interface
*   **PostgreSQL Abstraction**: Custom database layer with transaction support and connection pooling
*   **Structured Logging**: Comprehensive observability using `go.uber.org/zap`
*   **Configuration Management**: Viper-based config with environment variable override and validation
*   **REST API Design**: RESTful `/v1/{resourceType}/{serviceName}/...` routes with middleware error handling
*   **Discord API Integration**: Built-in service interaction via `discordgo` library
*   **Modular Services**: Currently features "Eris" service; extensible for additional implementations

**Architecture**: Request flow through error middleware → dynamic dispatch → handler logic → database transactions → standardized JSON responses.

#### **[Wednesday Oxidize](https://github.com/ckaspian/wednesday-oxidize)**
> *Rust, Systems Architecture, Async Runtime*

A **Rust rewrite** of core Wednesday infrastructure, focusing on memory safety, performance, and modern async patterns. Demonstrates expertise in translating complex systems code from imperative to functional paradigms while maintaining correctness and performance characteristics.

**Key Focus**: Leveraging Rust's type system for compile-time correctness, exploring async/await patterns at scale, and systems-level optimization.

#### **[CigFinder](https://github.com/ckaspian/CigFinder)**
> *C, Pattern Matching, Signature Detection*

A **high-performance signature detection tool** written in pure C using YARA-style pattern matching. Optimized for minimal overhead scanning with direct byte-sequence identification.

**Technical Highlights**:
*   Efficient memory footprint with zero external dependencies
*   Direct binary pattern matching without regex overhead
*   Cross-platform POSIX compliance

#### **Runtime Modifications & Protocol Engineering**
> *C#, BepInEx, MelonLoader, Protobuf, Dioxus*

**Open-source contributions** demonstrating expertise in:
*   **Runtime Injection**: Hook-based patching of compiled IL/mono assemblies
*   **Protocol Buffers**: Integration with Protobuf serialization, with bug fixes contributed upstream
*   **Reverse Engineering**: Decompilation analysis and state management in game engines
*   **Dioxus Integration**: Rendering pipeline improvements and component architecture

**Contributions Include**:
*   Bug fixes in Protocol Buffers message serialization
*   Dioxus rendering optimization
*   State management hooks for dynamic runtime environments

---

### 📝 Writing & Thought Leadership
*From [wednesday.wtf](https://wednesday.wtf)*

Technical blog exploring systems programming, Rust ecosystems, backend architecture, and optimization strategies. Recent pieces examine the intersection of performance, safety, and ergonomics in modern systems languages.

---

> "An idiot admires complexity, a genius admires simplicity." — Terry A. Davis
