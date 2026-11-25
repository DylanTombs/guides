# How do I learn Rust? I got you 🦀

**Live page:** https://dylantombs.github.io/guides/rust/

![A terminal showing the Rust repository as a red ASCII crab](crab-terminal.jpg)
<sub>Image: [Rust 101](https://medium.com/codex/rust-101-everything-you-need-to-know-about-rust-f3dd0ae99f4c)</sub>

Rust is a programming language built to be fast without the memory bugs that C and C++ are known for. Google's Android team reports **1000x lower memory-safety vulnerability density** in Rust than in their C/C++ (Google security blog, Nov 2025). Discord rewrote a service from Go to Rust to get rid of garbage-collector latency spikes (2020).

## Why Rust

- [Google: Rust in Android](https://blog.google/security/rust-in-android-move-fast-fix-things/): how 1000x fewer memory bugs looks in a real codebase.
- [Why Discord switched from Go to Rust](https://discord.com/blog/why-discord-is-switching-from-go-to-rust): what happened when garbage collection caused latency spikes.
- [Rust: a language for the next 40 years](https://chariotsolutions.com/screencast/philly-ete-2019-carol-nichols-rust-a-language-for-the-next-40-years/): a talk by Carol Nichols, co-author of the Rust Book.

## Learn it, in this order

1. [Rust 101](https://medium.com/codex/rust-101-everything-you-need-to-know-about-rust-f3dd0ae99f4c): a 9-minute overview, so the rest makes sense.
2. [The Rust Book, chapters 1-8](https://doc.rust-lang.org/book/): the core of the language, explained properly and for free.
3. [Rustlings](https://github.com/rust-lang/rustlings): small exercises to do alongside the book.
4. [Google's Comprehensive Rust](https://google.github.io/comprehensive-rust/): the course Google uses internally to teach Rust to its engineers.
5. [Microsoft's RustTraining books](https://microsoft.github.io/RustTraining/): free books that bridge to Rust if you already know Python, C# or C++.

## Then build (easiest first)

| # | Project | Difficulty |
|---|---|---|
| 1 | [Your own grep](https://rust-cli.github.io/book/tutorial/index.html): a command line app in about 15 minutes | Easy |
| 2 | [A multithreaded web server](https://doc.rust-lang.org/book/ch21-00-final-project-a-web-server.html): the Rust Book's final project | Medium |
| 3 | [Your own operating system](https://os.phil-opp.com/): a free blog series that builds a small OS step by step | Hard |

## Try it now

[Rust Playground](https://play.rust-lang.org/): write and run Rust in your browser. No install.
