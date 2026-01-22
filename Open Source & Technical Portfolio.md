# TECHNICAL PORTFOLIO – OPEN SOURCE PROJECTS & CONTRIBUTIONS

### 1. THE KMX-SYSTEMS ECOSYSTEM
*A modular, high-performance C++20 framework architected to replace standard heavy dependencies in embedded and real-time environments.*

*   **`kmx-geoindex` (Geospatial):**
    *   High-performance spatial indexing library implementing **Hexagonal Grid Systems**.
    *   Used for efficient geospatial data querying and discretization (similar to Uber H3).
*   **`kmx-aio` (High-Performance I/O):**
    *   Asynchronous I/O engine wrapping Linux `epoll` / `io_uring`.
    *   Designed for high-throughput, non-blocking network services.
*   **`kmx-asn1-ber-encoding` & `kmx-mib-parser` (Telecom/Networking):**
    *   A complete compiler stack for telecommunication protocols.
    *   Includes an **ANTLR4-based** parser for SNMP MIB files and a custom **BER (Basic Encoding Rules)** encoder/decoder.
    *   Enables raw protocol handling without external heavy libraries.
*   **`kmx-unit` (Safety/Physics):**
    *   Type-safe **Dimensional Analysis** library.
    *   Prevents unit conversion errors (e.g., meters vs. feet) at compile-time, critical for automotive and aerospace safety.
*   **`kmx-h265-gpu-support` (Media/Compute):**
    *   Library for querying and managing **HEVC (H.265)** hardware acceleration capabilities on GPUs.
*   **`kmx-gis` & `uat-bbox`:**
    *   Coordinate transformation engines (WGS84 <-> Stereo70) and bounding box calculators for GIS data.

---

### 2. PERSONAL GITHUB HIGHLIGHTS
*Key contributions demonstrating expertise in Modern C++, Concurrency, and Architecture.*

*   **`co_fsm` (C++20 Coroutines):**
    *   **Description:** A header-only Finite State Machine library based on C++20 Coroutines.
    *   **Innovation:** Allows developers to write asynchronous state logic in a sequential, linear style, eliminating "callback hell."
*   **`apollo` (Baidu Apollo Auto Fork):**
    *   **Description:** Open-source autonomous driving platform.
    *   **Contribution:** Refactored the **High-Definition (HD) Map** module to remove code duplication and improve maintainability of the map engine.
*   **`VulkanSceneGraph` & `rocky` (Graphics/Simulation):**
    *   **Contribution:** Contributor to the modern Vulkan-based scene graph and the "Rocky" 3D digital globe engine.
    *   **Skill:** Demonstrates ability to work with complex 3D rendering pipelines and geospatial visualization.
*   **`open62541pp` (Industrial IoT):**
    *   **Description:** C++ wrapper for the `open62541` OPC UA implementation.
    *   **Impact:** Enables modern C++ applications to interface with Industry 4.0 manufacturing hardware.

---

### 3. SPECIALIZED TECHNICAL PROJECTS (By Domain)

**Concurrency & System Architecture**
*   **`task-processor`:** A custom thread pool and task scheduler using atomics and memory barriers.
*   **`custom-allocator`:** High-performance memory allocator handling fragmentation and locality.
*   **`read_write_mutex`:** Custom implementation of Reader-Writer locks for specific starvation policies.

**Network & Connectivity**
*   **`websockets-demo` & `async-api-demo`:** Demonstrations of C++20 coroutine-based asynchronous web servers.
*   **`asio-ssl-mutual-auth`:** Implementation of Mutual TLS (mTLS) authentication using Boost.ASIO.
*   **`http-download-manager`:** Multi-threaded HTTP downloader supporting Range headers and connection pooling.

**Parsers & Compilers**
*   **`xsd2cpp-gen`:** A code generator that compiles XML Schema Definitions (XSD) into static C++ classes.
*   **`smi-parser` & `oid_ncode`:** Low-level tools for handling SMI (Structure of Management Information) and OID encoding.
*   **`kmx-xpar`:** A minimalist, event-based XML parser optimized for embedded memory constraints.

**Algorithms & Research**
*   **`generic-a-star`:** A template-based implementation of the A* pathfinding algorithm, decoupled from the graph structure.
*   **`kmx-fft`:** Fast Fourier Transform implementation for signal processing.
*   **`nlp-romanian`:** Natural Language Processing tools (stemming/tokenization) for the Romanian language.
*   **`hello_world_wasm`:** Experiments with Emscripten/WebAssembly to port C++ logic to the browser.
