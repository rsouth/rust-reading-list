# Rust 🦀 Reading List

Collection of hopefully useful, semi-organised links as a reference from my first few weeks with Rust. Happy to accept PRs for any other useful links!

## Contents

- [🌟 References](#-references)
- [🚀 Performance](#-performance)
  * [SIMD](#simd)
- [🔄 Borrowing and Lifetimes etc](#-borrowing-and-lifetimes-etc)
- [🔀 Async](#-async)
- [🦀 Idiomatic Rust](#-idiomatic-rust)
- [📰 Articles](#-articles)
- [🎶 Useful notes](#-useful-notes)
- [Other resources](#other-resources)
- [🧰 Crates](#-crates)
  * [Actix](#actix)
  * [Tokio](#tokio)
  * [GUI](#gui)
  * [Serde](#serde)
  * [Misc](#misc)
- [Series](#series)
- [✔️ Testing](#-testing)
- [📏 Benching](#-benching)
  * [Criterion](#criterion)
- [Other Lists](#other-lists)
- [Rust for X Programmers](#rust-for-x-programmers)
  * [☕ ... Java](#--java)
  * [... Scala](#-scala)
  * [🐍 ... Python](#--python)
- [💾 Downloads](#-downloads)

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

How to write CRaP Rust code (Correct, Readable and Performant)
https://blog.logrocket.com/how-to-write-crap-rust-code/

Optimizing your code
https://dev.to/luzero/optimizing-your-code-48n1

From 48s to 5s - optimizing a 350 line pathtracer in Rust
https://blog.usejournal.com/from-48s-to-5s-optimizing-a-350-line-pathtracer-in-rust-191ab4a1a412

Acheiving warp speed with Rust
http://troubles.md/rust-optimization/

"What The Hardware Does" is not What Your Program Does
https://www.ralfj.de/blog/2019/07/14/uninit.html

🎥 Scott Meyers: Cpu Caches and Why You Care
https://www.youtube.com/watch?v=WDIkqP4JbkE

Branch prediction - Why is processing a sorted array faster than processing an unsorted array?
https://stackoverflow.com/a/11227902

Where should I start if I want to squeeze out as much performance as I can from my rust code?
https://www.reddit.com/r/rust/comments/bb5lnj/where_should_i_start_if_i_want_to_squeeze_out_as/

Fastware Workshop
http://troubles.md/posts/rustfest-2018-workshop/

Top-Down performance analysis methodology
https://dendibakh.github.io/blog/2019/02/09/Top-Down-performance-analysis-methodology

https://llogiq.github.io/2017/06/01/perf-pitfalls.html

https://github.com/dgryski/go-perfbook

LLVM reference and Godbolt Compiler Explorer
http://llvm.org/docs/LangRef.html && https://rust.godbolt.org/

Performance Tuning In Rust Using Benchmarking And Perf
https://www.worthe-it.co.za/blog/2018-09-23-performance-tuning-in-rust.html

Optimizations: The speed size tradeoff - The Embedded Rust Book
https://docs.rust-embedded.org/book/unsorted/speed-vs-size.html

https://www.youtube.com/results?search_query=mike+acton

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


## 🧵 Async

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

Learning Rust by solving all 189 problems from the “Cracking the Coding Interview” book
https://hackernoon.com/programming-in-rust-the-good-the-bad-the-ugly-d06f8d8b7738

Object-Oriented Programming in Rust
https://blog.devgenius.io/object-oriented-programming-in-rust-691baf4d2996

So you want to write object oriented Rust
https://blog.darrien.dev/posts/so-you-want-to-object/

These Modern Programming Languages Will Make You Suffer
https://betterprogramming.pub/modern-languages-suck-ad21cbc8a57c

https://limpet.net/mbrubeck/2019/02/07/rust-a-unique-perspective.html

Foreign function interface (FFI) - Rust Design Patterns
https://rust-unofficial.github.io/patterns/idioms/ffi/intro.html

Building a Rust Web Browser
https://joshondesign.com/2020/03/10/rust_minibrowser

🎥 Is It Time to Rewrite the Operating System in Rust?
https://www.youtube.com/watch?t=2457&v=HgtRAbE1nBM&feature=youtu.be

The Speed of Rust vs C
https://kornel.ski/rust-c-speed

https://brson.github.io/fireflowers/


## 🎶 Useful notes

Stack Overflow - What is the difference between iter and into_iter?
https://stackoverflow.com/questions/34733811/what-is-the-difference-between-iter-and-into-iter
https://hermanradtke.com/2015/06/22/effectively-using-iterators-in-rust.html

Rust modules vs files
https://fasterthanli.me/articles/rust-modules-vs-files

Stack Overflow - Rust package with both a library and a binary?
https://stackoverflow.com/questions/26946646/rust-package-with-both-a-library-and-a-binary

https://www.lpalmieri.com/posts/2020-09-27-zero-to-production-4-are-we-observable-yet/

https://doc.rust-lang.org/book/ch14-03-cargo-workspaces.html

https://doc.rust-lang.org/rust-by-example/flow_control/match/destructuring/destructure_structures.html

Everything you need to know about cross compiling Rust programs
https://github.com/japaric/rust-cross


## 🗃️ Other resources

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

> TODO Organise crates by functional areas - use this space to provide useful links relating to great crates, not just linking to the crate.

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

https://github.com/tauri-apps/tauri

https://www.boringcactus.com/2020/08/21/survey-of-rust-gui-libraries.html

https://www.areweguiyet.com/

### Serde

https://serde.rs/attr-default.html

###

https://github.com/rayon-rs/rayon

### raqote

https://crates.io/crates/raqote

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

📘 List of Rust books
https://github.com/sger/RustBooks

Not Rust specific, but: A public list of APIs
https://github.com/n0shake/Public-APIs


## Rust for ... Programmers

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

"Idiomatic Rust - Writing concise and elegant Rust code"
https://github.com/rsouth/rust-reading-list/blob/main/Idiomatic_Rust_-_Matthias_Endler_-_FOSDEM_2018.pdf

"Rust Container Cheat Sheet"
https://github.com/rsouth/rust-reading-list/blob/main/Rust%20container%20cheat%20sheet.pdf

## Are we ... yet?

List of "Are we ... yet" sites on Moz wiki
https://wiki.mozilla.org/Areweyet

 ... 👾
https://arewegameyet.rs/

 ... 🕸️
https://arewewebyet.org/

 ... 🖱️
https://areweguiyet.com/

## Blogs

http://troubles.md/

https://www.ralfj.de/blog/

Nicholas Nethercote - personal site https://nnethercote.github.io/ and Moz blog https://blog.mozilla.org/nnethercote/category/performance/

https://llogiq.github.io/


# Dumping ground

> Everything below here is uncategorised, dumped for later review
 
https://github.com/ctjhoa/rust-learning
ctjhoa/rust-learning
A bunch of links to blog posts, articles, videos, etc for learning Rus

https://github.com/matthieu-m/ghost-collections
matthieu-m/ghost-collections - Safe collections written in stable Rust, based on GhostCell and StaticRc

http://www.serpentine.com/criterion/tutorial.html

https://docs.rs/slotmap/1.0.3/slotmap/
slotmap

https://www.christopherbiscardi.com/i-have-some-json-with-a-ton-of-test-cases-how-do-i-use-that-in-rust
I have some JSON with a ton of test cases, how do I use that in Rust?

https://lucumr.pocoo.org/

https://without.boats/blog/

https://hoverbear.org/
A computer scientist working in open source towards a more hopeful future.

https://steveklabnik.com/
Steve Klabnik's personal website

https://fasterthanli.me/
amos loves to tinker

https://blog.rust-lang.org/
The Rust Programming Language Blog

https://github.com/routerify/routerify

https://deterministic.space/high-performance-rust.html
Cheap tricks for high-performance Rust

https://gist.github.com/jFransham/369a86eff00e5f280ed25121454acec1
Rust Optimization.md

http://likebike.com/posts/How_To_Write_Fast_Rust_Code.html

https://blog.rust-lang.org/2015/04/10/Fearless-Concurrency.html
Fearless Concurrency with Rust | Rust Blog

https://mudit.blog/rust-tips-and-tricks/
Rust lang Tips and Tricks | Mudit Gupta's Blog

https://jondot.medium.com/my-key-learnings-after-30-000-loc-in-rust-a553e6403c19
My Key Learnings after 30,000 LOC in Rust

https://users.rust-lang.org/t/mixed-up-borrowing/54288
The Rust Programming Language Forum - Mixed up borrowing

https://fasterthanli.me/articles/i-want-off-mr-golangs-wild-ride
I want off Mr. Golang's Wild Ride

https://cheats.rs/#memory-lifetimes

https://doc.rust-lang.org/edition-guide/rust-2018/simd-for-faster-computing.html
SIMD for faster computing - The Edition Guide

https://news.ycombinator.com/item?id=24835357
Assorted Thoughts on Zig and Rust
https://scattered-thoughts.net/writing/assorted-thoughts-on-zig-and-rust/

https://dev.to/luzero/optimizing-your-code-48n1
Optimizing your code - This is the second post about optimization, in the first one I tried to give you the big picture of m...

https://news.ycombinator.com/item?id=22818150
I can't keep up with idiomatic Rust
https://timidger.github.io/posts/i-cant-keep-up-with-idiomatic-rust/

https://speakerdeck.com/mre/idiomatic-rust-writing-concise-and-elegant-rust-code

https://blog.logrocket.com/understanding-lifetimes-in-rust/
Understanding lifetimes in Rust - LogRocket Blog

https://medium.com/@carllerche/announcing-tokio-df6bb4ddb34
Announcing Tokio

https://newrustacean.com/show_notes/e002/index.html
show_notes::e002 - Rust

https://github.com/smoltcp-rs/smoltcp
smoltcp-rs/smoltcp - a smol tcp/ip stack

http://manishearth.github.io/blog/2017/01/11/rust-tidbits-what-is-a-lang-item/
Rust Tidbits: What is a lang item?

https://github.com/silvia-odwyer/photon/native-tutorial/

https://docs.microsoft.com/en-us/learn/modules/rust-memory-management/1-what-is-ownership
What is ownership? - Learn about how memory is managed through ownership.

https://thoughtram.io/rust-and-nickel/#/11
Rust - Rethinking Systems Programming

https://medium.com/learning-rust/rust-basics-e73304ab35c7
RUST BASICS - "A language that doesn’t affect the way you think about programming, is not worth knowing."

https://gist.github.com/brson/a324c83a6af6a8a78dfaa9d33eb9b48e
Gist - A collection of notable Rust blog posts

http://smallcultfollowing.com/babysteps/blog/2015/04/06/modeling-graphs-in-rust-using-vector-indices/
Modeling graphs in Rust using vector indices

https://tokio.rs/tokio/tutorial

https://doc.rust-lang.org/1.0.0/style/ownership/builders.html

https://docs.rs/imageproc/0.22.0/imageproc/
imageproc - Rust

https://doc.rust-lang.org/std/boxed/index.html
std::boxed - A pointer type for heap allocation.

http://likebike.com/posts/How_To_Write_Fast_Rust_Code.html

https://jondot.medium.com/my-key-learnings-after-30-000-loc-in-rust-a553e6403c19
My Key Learnings after 30,000 LOC in Rust

https://doc.rust-lang.org/rust-by-example/fn/closures/closure_examples/iter_any.html
Iterator::any - Rust By Example

https://ryhl.io/
Alice Ryhl – Personal website

https://ryhl.io/blog/async-what-is-blocking/
Async: What is blocking? – Alice Ryhl

https://medium.com/swlh/why-you-should-learn-rust-df1caf11d911
Why You Should Learn Rust

https://stevedonovan.github.io/rust-gentle-intro/1-basics.html
Basics - A Gentle Introduction to Rust - Introduction to the Rust language, standard library and ecosystem

https://learning-rust.github.io/index.html
Rust Programming Language Tutorials

https://gist.github.com/rylev/f76b8e9567a722f1b157a69a4f98f1c1
Gist - How to Learn Rust

https://dhghomon.github.io/easy_rust/Chapter_8.html
Type inference - Easy Rust

https://serokell.io/blog/learn-rust
Want to learn Rust but don't know where to start? In this article, we have gathered 17 awesome books, articles, videos, and other resources that will help you.

https://danielkeep.github.io/itercheat_baked.html

https://fasterthanli.me/articles/a-half-hour-to-learn-rust
A half-hour to learn Rust - fasterthanli.me

https://towardsdatascience.com/you-want-to-learn-rust-but-you-dont-know-where-to-start-fc826402d5ba
A Complete Resource for Rust Beginners

