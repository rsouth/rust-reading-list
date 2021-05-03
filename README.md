# Rust 🦀 Reading List

Collection of hopefully useful, semi-organised links as a reference from my first few weeks with Rust. Happy to accept PRs for any other useful links!

  * [Files](#files)
  * [Common](#common)
  * [Performance](#performance)
    + [SIMD](#simd)
  * [Borrowing and Lifetimes etc](#borrowing-and-lifetimes-etc)
  * [Async](#async)
  * [Idiomatic Rust](#idiomatic-rust)
  * [Articles](#articles)
  * [Useful notes](#useful-notes)
  * [Other resources](#other-resources)
  * [Crates](#crates)
    + [Actix](#actix)
    + [Tokio](#tokio)
    + [GUI](#gui)
    + [Serde](#serde)
    + [Misc](#misc)
  * [Series](#series)
  * [Testing](#testing)
  * [Benching](#benching)
    + [Criterion](#criterion)

<small><i><a href='http://ecotrust-canada.github.io/markdown-toc/'>Table of contents generated with markdown-toc</a></i></small> :thumbsup:

## 🌟 References

> **The Book** and other useful reference material.

Entrypoint for various rust-lang documentation: [The Book](https://doc.rust-lang.org/book/), [RBE](https://doc.rust-lang.org/stable/rust-by-example/), [std lib](https://doc.rust-lang.org/std/index.html), [Compiler Error Index](https://doc.rust-lang.org/error-index.html) and loads more.
https://www.rust-lang.org/learn

🙏 The Rust Book
https://doc.rust-lang.org/book/ / Nightly: https://doc.rust-lang.org/nightly/book/

Rust Bookbook - Collection of useful Rust code examples
https://rust-lang-nursery.github.io/rust-cookbook/

Rust by Example (RBE) - Collection of runnable examples that illustrate various Rust concepts and standard libraries
https://doc.rust-lang.org/stable/rust-by-example/

Writing Rust in Easy English
https://dhghomon.github.io/easy_rust/


## 🚀 Performance

The Rust Performance Book
https://nnethercote.github.io/perf-book/general-tips.html

(Correct, Readable and Performant) How to write CRaP Rust code
https://blog.logrocket.com/how-to-write-crap-rust-code/

Optimizing your code
https://dev.to/luzero/optimizing-your-code-48n1

From 48s to 5s - optimizing a 350 line pathtracer in Rust
https://blog.usejournal.com/from-48s-to-5s-optimizing-a-350-line-pathtracer-in-rust-191ab4a1a412

Acheiving warp speed with Rust
http://troubles.md/rust-optimization/

"What The Hardware Does" is not What Your Program Does
https://www.ralfj.de/blog/2019/07/14/uninit.html

code::dive conference 2014 - Scott Meyers: Cpu Caches and Why You Care
https://www.youtube.com/watch?v=WDIkqP4JbkE

Why is processing a sorted array faster than processing an unsorted...
https://stackoverflow.com/a/11227902/435253

Where should I start if I want to squeeze out as much perf...
https://www.reddit.com/r/rust/comments/bb5lnj/where_should_i_start_if_i_want_to_squeeze_out_as/

https://www.youtube.com/results?search_query=mike+acton

Fastware Workshop
http://troubles.md/posts/rustfest-2018-workshop/

Top-Down performance analysis methodology
https://dendibakh.github.io/blog/2019/02/09/Top-Down-performance-analysis-methodology

https://llogiq.github.io/2017/06/01/perf-pitfalls.html

https://github.com/dgryski/go-perfbook

LLVM reference and Godbolt Compiler Explorer
http://llvm.org/docs/LangRef.html && https://rust.godbolt.org/

https://www.worthe-it.co.za/blog/2018-09-23-performance-tuning-in-rust.html

https://blog.mozilla.org/nnethercote/category/performance/

Optimizations: The speed size tradeoff - The Embedded Rust Book
https://docs.rust-embedded.org/book/unsorted/speed-vs-size.html

### SIMD

SIMD for faster computing
https://doc.rust-lang.org/edition-guide/rust-2018/simd-for-faster-computing.html


## 🔄 Borrowing and Lifetimes etc

References and Borrowing
http://web.mit.edu/rust-lang_v1.25/arch/amd64_ubuntu1404/share/doc/rust/html/book/first-edition/references-and-borrowing.html

What is Ownership?
https://doc.rust-lang.org/book/ch04-01-what-is-ownership.html

Learning Rust: Memory, Ownership and Borrowing
https://www.youtube.com/watch?v=8M0QfLUDaaA


## 🔀 Async

https://tokio.rs/blog/2020-04-preemption#a-note-on-blocking

Async: What is blocking? – Alice Ryhl (& Alice and other Tokio dev writing in general are must-reads for async)
https://ryhl.io/blog/async-what-is-blocking/

https://tokio.rs/tokio/tutorial/spawning#concurrency

https://stackoverflow.com/questions/55552413/what-is-the-difference-between-then-and-then-and-or-else-in-rust-futures

Futures Explained in 200 Lines of Rust
https://cfsamson.github.io/books-futures-explained/


## 🦀 Idiomatic Rust

https://cheats.rs/#idiomatic-rust

Thinking In Rust Part 1: Types
https://llblumire.co.uk/thinking-in-rust-part-1-types/

Error Handling in Rust - Andrew Gallant's Blog
https://blog.burntsushi.net/rust-error-handling/

Rust lang Tips and Tricks | Mudit Gupta's Blog
https://mudit.blog/rust-tips-and-tricks/

Unwrap and Expect
https://learning-rust.github.io/docs/e4.unwrap_and_expect.html

https://speakerdeck.com/mre/idiomatic-rust-writing-concise-and-elegant-rust-code

https://learning-rust.github.io/docs/e3.option_and_result.html

https://llogiq.github.io/2015/07/30/traits.html

Basic Rust iterator usage
https://github.com/rustomax/rust-iterators

Design Patterns https://rust-unofficial.github.io/patterns/ (https://github.com/rust-unofficial/patterns)


## 📰 Articles

https://hackernoon.com/programming-in-rust-the-good-the-bad-the-ugly-d06f8d8b7738

Object-Oriented Programming in Rust
https://blog.devgenius.io/object-oriented-programming-in-rust-691baf4d2996

https://blog.darrien.dev/posts/so-you-want-to-object/

These Modern Programming Languages Will Make You SufferThese Modern Programming Languages Will Make You Suffer
https://betterprogramming.pub/modern-languages-suck-ad21cbc8a57c

https://limpet.net/mbrubeck/2019/02/07/rust-a-unique-perspective.html

Foreign function interface (FFI) - Rust Design Patterns
https://rust-unofficial.github.io/patterns/idioms/ffi/intro.html

https://joshondesign.com/2020/04/13/browser_render

🎥 Is It Time to Rewrite the Operating System in Rust?
https://www.youtube.com/watch?t=2457&v=HgtRAbE1nBM&feature=youtu.be

The Speed of Rust vs C
https://kornel.ski/rust-c-speed


## 🎶 Useful notes

Stack Overflow - What is the difference between iter and into_iter?
https://stackoverflow.com/questions/34733811/what-is-the-difference-between-iter-and-into-iter

Rust modules vs files
https://fasterthanli.me/articles/rust-modules-vs-files

Rust package with both a library and a binary?
https://stackoverflow.com/questions/26946646/rust-package-with-both-a-library-and-a-binary

https://www.lpalmieri.com/posts/2020-09-27-zero-to-production-4-are-we-observable-yet/

https://doc.rust-lang.org/book/ch14-03-cargo-workspaces.html

https://doc.rust-lang.org/rust-by-example/flow_control/match/destructuring/destructure_structures.html

Everything you need to know about cross compiling Rust programs!
https://github.com/japaric/rust-cross


## Other resources

Exercism.
https://exercism.io/tracks/rust

How to Learn Rust
https://gist.github.com/rylev/f76b8e9567a722f1b157a69a4f98f1c1#:~:text=The%20best%20way%20to%20learn,to%20more%20real%20world%20projects.

https://caniuse.rs/

Rust container cheat sheet
https://docs.google.com/presentation/d/1q-c7UAyrUlM-eZyTo1pd8SZ0qwA_wYxmPZVOQkoDmH4/mobilepresent?slide=id.p

Easy Rust book
https://dhghomon.github.io/easy_rust/Chapter_13.html

Rust Programming Language Tutorials
https://medium.com/learning-rust

https://learning-rust.github.io/

https://carols10cents.github.io/rust-conversion-reference/

Rust Omnibus (FFI) How to use Rust code in other languages
https://jakegoulding.com/rust-ffi-omnibus/
        
The Little Book of Rust Macros
https://danielkeep.github.io/tlborm/book/index.html

Software Projects. Code Samples. Software Links
https://jimfawcett.github.io/SiteMap.html


## 🧰 Crates

### Actix

https://alinex.gitlab.io/rust/crates/actix/

https://docs.rs/actix/0.11.1/actix/fut/future/trait.ActorFuture.html

https://github.com/actix/actix/issues/291

https://www.reddit.com/r/actix/comments/cgmsqm/struggling_with_async_message_results/

https://www.reddit.com/r/actix/comments/dl1gy4/communication_between_two_actors/

https://actix.rs/docs/testing/

https://www.zupzup.org/rust-webapp/index.html

https://mattgathu.github.io/2020/04/16/actix-web-error-handling.html

Are we observable yet? An introduction to Rust telemetry
https://www.amarjanica.com/mocking-actix-actor-without-getting-a-gray-hair/index.html

https://actix.rs/docs/websockets/

https://docs.rs/actix-broker/0.4.0/actix_broker/

Actix - actor framework in Rust
https://actix.rs/book/actix/sec-1-getting-started.html


### Tokio

A runtime for writing reliable network applications without compromising speed.
https://docs.rs/tokio/1.4.0/tokio/

### GUI

https://github.com/linebender/druid

### Serde

https://serde.rs/attr-default.html

### Misc

https://crates.io/crates/async-trait

Anyhow - Flexible concrete Error type built on std::error::Error
https://lib.rs/crates/anyhow


## Series

🎥 Doug Milford's Rust series
https://www.youtube.com/playlist?list=PLLqEtX6ql2EyPAZ1M2_C0GgVd4A-_L4_5

🎥 Easy Rust playlist
https://www.youtube.com/watch?v=-lYeJeQ11OI&list=PLfllocyHVgsRwLkTAhG0E-2QxCf-ozBkk

Rust for OOP - Series Introduction
https://oribenshir.github.io/afternoon_rusting/blog/rust-for-oop

Introduction to the Rust language, standard library and ecosystem
https://stevedonovan.github.io/rust-gentle-intro/object-orientation.html

Learning Rust With Entirely Too Many Linked Lists
https://rust-unofficial.github.io/too-many-lists/

Rust Programming Language Tutorial – How to Build a To-Do List App
https://www.freecodecamp.org/news/how-to-build-a-to-do-app-with-rust/amp/

All the resources you need to give yourself a world class computer science education
https://teachyourselfcs.com/

Learn Rust in Y Minutes
https://learnxinyminutes.com/docs/rust/

Microsoft's Rust tutorials
https://docs.microsoft.com/en-us/learn/paths/rust-first-steps/

https://www.ralfj.de/projects/rust-101/main.html


## ✔️ Testing

https://knowitlabs.no/rust-2020-testing-4ab3d80112ba

https://archive.fosdem.org/2018/schedule/event/rust_testing_mocking/attachments/slides/2113/export/events/attachments/rust_testing_mocking/slides/2113/testing_in_rust_by_donald_whyte.pdf


## 📏 Benching

### Criterion

https://github.com/bheisler/criterion.rs

https://bheisler.github.io/criterion.rs/book/index.html


## Other Lists

https://github.com/ctjhoa/rust-learning

https://github.com/kud1ing/awesome-rust / https://project-awesome.org/rust-unofficial/awesome-rust

Awesomo Rust
https://github.com/lk-geimfari/awesomo/blob/master/languages/RUST.md

List of Rust books
https://github.com/sger/RustBooks

Not Rust specific, but: A public list of APIs
https://github.com/n0shake/Public-APIs


## Rust for X Programmers

### ☕ ... Java

https://llogiq.github.io/2016/02/28/java-rust.html

https://gist.github.com/Kimundi/8391398

https://overexact.com/rust-for-professionals/

https://leshow.github.io/post/rust_for_java_devs/

### ... Scala

https://beachape.com/blog/2017/05/24/rust-from-scala/

### 🐍 ... Python

https://lucumr.pocoo.org/2015/5/27/rust-for-pythonistas/


## 💾 Downloads

Useful / interesting files, mirrored here lest they move or vanish.

"Is Rust Used Safely by Software Developers"
https://github.com/rsouth/rust-note-dump/blob/main/2007.00752.pdf

"Safe Systems Programming in Rust"
https://github.com/rsouth/rust-note-dump/blob/main/2021-rustbelt-cacm-final.pdf

"What Every Programmer Should Know About Memory"
https://github.com/rsouth/rust-note-dump/blob/main/cpumemory.pdf

Packt "Learning Rust" Free eBook
https://github.com/rsouth/rust-note-dump/blob/main/rust.pdf

"Testing in Rust"
https://github.com/rsouth/rust-note-dump/blob/main/testing_in_rust_by_donald_whyte.pdf


# Dumping ground

> Everything below here is uncategorised, dumped for later review
 


