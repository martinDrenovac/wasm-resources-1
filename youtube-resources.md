# WASM youtube (by date?)

## 2025
- [Real World WASI Components by Colin Murphy @ Wasm I/O 2025](https://www.youtube.com/watch?v=QebWw3_K1_4)
- [Keynote: Incrementally Extending WASI 0.2 to 0.3 and Beyond - Luke Wagner](https://www.youtube.com/watch?v=W3f8AAte0LM) - This talk will explain the progress since WASI 0.2, the next big milestone, WASI 0.3, and what comes after that.
- [Unlocking Observability in WebAssembly with OpenTelemetry by Caleb Schoepp @ Wasm I/O 2025](https://www.youtube.com/watch?v=iKh8YlJh618) - how OpenTelemetry integrates with WebAssembly
- [The Browser is the Computer! by Daniel Lopez & Angel De Miguel @ Wasm I/O 2025](https://www.youtube.com/watch?v=T5cT3U2afC0) - run full-stack development environments completely inside your browser
- [Flutter, Dart, and WASM-GC: A new model for Web applications by Kevin Moore @ Wasm I/O 2023](https://www.youtube.com/watch?v=Nkjc9r0WDNo) - Support for garbage collection within WebAssembly (WASM-GC) will bring a host of new languages and frameworks to the web app space. Learn how the Dart and Flutter teams at Google are building on WASM-GC (among other upcoming standards) to bring richer, faster, more consistent applications to the web Until now, WASM-compiled browser applications have been mostly limited to systems programming languages – allowing a number of traditionally desktop experiences to run on the web. (Think AutoCad, PhotoShop, Google Earth.) The implementation of WASM-GC across WASM runtimes will bring a set of new languages and frameworks to an ecosystem dominated by C/C++ and Rust. The open source Dart and Flutter projects at Google have spent over a year adding WebAssembly as a target platform with the hope of improving application load time and interactive performance for Flutter experiences on the web. This talk will cover how WASM-GC expands the WASM ecosystem.

- [From Cloud to Edge computing - Unleashing the power of WebAssembly at the edge by Alex Casalboni](https://www.youtube.com/watch?v=WEWMVFQjHcw) - In this session, we’ll dive deep into how WebAssembly enables lightweight, secure, and fast compute workloads at the edge, with an emphasis on real-world use cases that leverage Rust’s unique strengths for predictable performance and memory safety, while coexisting with cloud resources. We’ll showcase the architectural tradeoff and technical challenges we face at Edgee such as data sovereignty and security constraints to power features such as data collection and dynamic A/B testing.
We’ll share how we optimized our open-source Rust-based WebAssembly components for edge deployment. Join us to discover how to build architectures that seamlessly blend cloud and edge, unlocking a new level of responsiveness and efficiency.

## 2025 - user Group Conversations (youtube)
 - [State of WebAssembly 2025 | Ep 15 | WebAssembly Unleashed](https://www.youtube.com/watch?v=s210eA2N3bE) - very interesting conversation covering history of WASM and some comments on current work in pipeline
 - []()


## 2024
- [WebAssembly is taking over!](https://www.youtube.com/watch?v=er_WkZLX7DY) - Doug Anderson
- [WebAssembly: A new development paradigm for the web](https://www.youtube.com/watch?v=RcHER-3gFXI) - Chrome Developers
- [Integrating Apache Arrow on WASM using Component Model - Sehyo Chang, InfinyOn](https://www.youtube.com/watch?v=Fv74WX0Q03Q) - how the Stateful Dataflow (SDF) engine seamlessly integrates Apache Arrow with the WASM Component Model
- [Master WebAssembly: The Complete Course from Beginner to Advanced](https://www.youtube.com/watch?v=eYekV2Do0YU) - 3 hr intro from basics
- 
## Earlier 
- [An introduction to WebAssembly](https://www.youtube.com/watch?v=3sU557ZKjUs) - Guy Royce RedisLabs
- [Data Across the Wasm Boundary By Dan Phillips](https://www.youtube.com/watch?v=2GSlCFCuN8U) - Devoxx 2023 presentation
- [Taking WASI-Cloud-Core for a Spin - Jiaxiao Zhou, Microsoft & Joel Dice, Fermyon Technologies](https://www.youtube.com/watch?v=W-ubCAMAJQc) - WASI-Cloud-Core is a WebAssembly Systems Interface (WASI) proposal aimed to provide a generic way for WASI applications to interact with service including key-value storage, pub/sub, sql databases, etc, regardless of platforms they are running on
- [HELLO WEBASSEMBLY - A BEGINNERS TUTORIAL TO CODING WEBASSEMBLY (WASM) BY HAND](https://www.youtube.com/watch?v=ojYEfRye6aE)
- [Tutorial Hands on with WebAssembly Microservices & Kubernetes- J Zhou D Justice K Goldenring R Matei](https://www.youtube.com/watch?v=LdsyS2cedOw) - This tutorial talk is meant to help you get started with WebAssembly (Wasm) on Kubernetes
- [Zig loves WASI! - Jakub Konka](https://www.youtube.com/watch?v=g_Degmqfo4Q) - Intro zig a front-end lang to wasm
- [Compiling To Web Assembly](https://www.youtube.com/watch?v=0WpplI0dd7w) - low level scheme coding into wasm, coding in .wat
- [USENIX Security '20 - Everything Old is New Again: Binary Security of WebAssembly](https://www.youtube.com/watch?v=glL__xjviro) - we analyze to what extent vulnerabilities are exploitable in WebAssembly binaries, and how this compares to native code. We find that many classic vulnerabilities which, due to common mitigations, are no longer exploitable in native binaries, are completely exposed in WebAssembly. Moreover, WebAssembly enables unique attacks, such as overwriting supposedly constant data or manipulating the heap using a stack overflow. We present a set of attack primitives that enable an attacker (i) to write arbitrary memory, (ii) to overwrite sensitive data, and (iii) to trigger unexpected behavior by diverting control flow or manipulating the host environment. We provide a set of vulnerable proof-of-concept applications along with complete end-to-end exploits, which cover three WebAssembly platforms. An empirical risk assessment on real-world binaries and SPEC CPU programs compiled to WebAssembly shows that our attack primitives are likely to be feasible in practice. Overall, our findings show a perhaps surprising lack of binary security in WebAssembly. We discuss potential protection mechanisms to mitigate the resulting risks.
