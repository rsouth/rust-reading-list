# rust-note-dump

Collection of hopefully useful, semi-organised links as a reference from my first few weeks with Rust. Happy to accept PRs for any other useful links!

  * [Common](#common)
  * [Performance](#performance)
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
- [Dumping ground](#dumping-ground)

<small><i><a href='http://ecotrust-canada.github.io/markdown-toc/'>Table of contents generated with markdown-toc</a></i></small> :thumbsup:


## Common

https://www.rust-lang.org/learn

The Rust Book: https://doc.rust-lang.org/nightly/book/

Collection of useful Rust code examples
https://rust-lang-nursery.github.io/rust-cookbook/

https://doc.rust-lang.org/stable/rust-by-example/
Rust by Example (RBE) is a collection of runnable examples that illustrate various Rust concepts and standard libraries.

https://dhghomon.github.io/easy_rust/
Writing Rust in Easy English


## Performance

https://nnethercote.github.io/perf-book/general-tips.html
The Rust Performance Book

https://kornel.ski/rust-c-speed

https://blog.logrocket.com/how-to-write-crap-rust-code/
(Correct, Readable and Performant) How to write CRaP Rust code - LogRocket Blog

https://dev.to/luzero/optimizing-your-code-48n1
Optimizing your code

https://blog.usejournal.com/from-48s-to-5s-optimizing-a-350-line-pathtracer-in-rust-191ab4a1a412
From 48s to 5s - optimizing a 350 line pathtracer in Rust

http://troubles.md/rust-optimization/
Acheiving warp speed with Rust

https://www.ralfj.de/blog/2019/07/14/uninit.html
"What The Hardware Does" is not What Your Program Does


## Borrowing and Lifetimes etc

http://web.mit.edu/rust-lang_v1.25/arch/amd64_ubuntu1404/share/doc/rust/html/book/first-edition/references-and-borrowing.html
References and Borrowing

https://doc.rust-lang.org/book/ch04-01-what-is-ownership.html
What is Ownership?

https://www.youtube.com/watch?v=8M0QfLUDaaA
Learning Rust: Memory, Ownership and Borrowing


## Async

https://tokio.rs/blog/2020-04-preemption#a-note-on-blocking


## Idiomatic Rust

https://cheats.rs/#idiomatic-rust

https://llblumire.co.uk/thinking-in-rust-part-1-types/
Thinking In Rust Part 1: Types

https://blog.burntsushi.net/rust-error-handling/
Error Handling in Rust - Andrew Gallant's Blog

https://mudit.blog/rust-tips-and-tricks/
Rust lang Tips and Tricks | Mudit Gupta's Blog

https://learning-rust.github.io/docs/e4.unwrap_and_expect.html
Unwrap and Expect

https://speakerdeck.com/mre/idiomatic-rust-writing-concise-and-elegant-rust-code

https://learning-rust.github.io/docs/e3.option_and_result.html

https://llogiq.github.io/2015/07/30/traits.html



## Articles

https://leshow.github.io/post/rust_for_java_devs/
Rust for Java Devs

https://hackernoon.com/programming-in-rust-the-good-the-bad-the-ugly-d06f8d8b7738

https://blog.devgenius.io/object-oriented-programming-in-rust-691baf4d2996
Object-Oriented Programming in Rust

https://blog.darrien.dev/posts/so-you-want-to-object/

https://betterprogramming.pub/modern-languages-suck-ad21cbc8a57c
These Modern Programming Languages Will Make You Suffer

https://limpet.net/mbrubeck/2019/02/07/rust-a-unique-perspective.html

https://rust-unofficial.github.io/patterns/idioms/ffi/intro.html
Foreign function interface (FFI) - Rust Design Patterns

https://joshondesign.com/2020/04/13/browser_render



## Useful notes

Stack Overflow - What is the difference between iter and into_iter?
https://stackoverflow.com/questions/34733811/what-is-the-difference-between-iter-and-into-iter

Rust modules vs files
https://fasterthanli.me/articles/rust-modules-vs-files

https://stackoverflow.com/questions/26946646/rust-package-with-both-a-library-and-a-binary
Rust package with both a library and a binary?

https://stackoverflow.com/questions/55552413/what-is-the-difference-between-then-and-then-and-or-else-in-rust-futures

https://www.lpalmieri.com/posts/2020-09-27-zero-to-production-4-are-we-observable-yet/

https://doc.rust-lang.org/book/ch14-03-cargo-workspaces.html

https://doc.rust-lang.org/rust-by-example/flow_control/match/destructuring/destructure_structures.html




## Other resources

https://github.com/sger/RustBooks

https://project-awesome.org/rust-unofficial/awesome-rust

https://exercism.io/tracks/rust
Exercism.

https://gist.github.com/rylev/f76b8e9567a722f1b157a69a4f98f1c1#:~:text=The%20best%20way%20to%20learn,to%20more%20real%20world%20projects.
How to Learn Rust

https://caniuse.rs/

https://docs.google.com/presentation/d/1q-c7UAyrUlM-eZyTo1pd8SZ0qwA_wYxmPZVOQkoDmH4/mobilepresent?slide=id.p
Rust container cheat sheet

Easy Rust book: https://dhghomon.github.io/easy_rust/Chapter_13.html

https://github.com/sger/RustBooks
List of Rust books.

https://github.com/kud1ing/awesome-rust


https://medium.com/learning-rust
Rust Programming Language Tutorials.

https://learning-rust.github.io/

https://carols10cents.github.io/rust-conversion-reference/

Rust Omnibus: https://jakegoulding.com/rust-ffi-omnibus/
    How to use Rust code in other languages
    
The Little Book of Rust Macros: https://danielkeep.github.io/tlborm/book/index.html

https://jimfawcett.github.io/SiteMap.html
Software Projects. Code Samples. Software Links

https://github.com/n0shake/Public-APIs
Not Rust specific, but: A public list of APIs from round the web.


## Crates

### Actix


https://alinex.gitlab.io/rust/crates/actix/

https://docs.rs/actix/0.11.1/actix/fut/future/trait.ActorFuture.html

https://github.com/actix/actix/issues/291

https://www.reddit.com/r/actix/comments/cgmsqm/struggling_with_async_message_results/

https://www.reddit.com/r/actix/comments/dl1gy4/communication_between_two_actors/

https://actix.rs/docs/testing/

https://www.zupzup.org/rust-webapp/index.html

https://mattgathu.github.io/2020/04/16/actix-web-error-handling.html

https://www.amarjanica.com/mocking-actix-actor-without-getting-a-gray-hair/index.html
Are we observable yet? An introduction to Rust telemetry | A learni...

https://actix.rs/docs/websockets/

https://docs.rs/actix-broker/0.4.0/actix_broker/

https://actix.rs/book/actix/sec-1-getting-started.html
Actix - actor framework in Rust


### Tokio

https://docs.rs/tokio/1.4.0/tokio/
A runtime for writing reliable network applications without compromising speed.


### GUI

https://github.com/linebender/druid
linebender/druid


### Serde

https://serde.rs/attr-default.html


### Misc

https://crates.io/crates/async-trait



## Series

Doug Milford's Rust series: https://www.youtube.com/playlist?list=PLLqEtX6ql2EyPAZ1M2_C0GgVd4A-_L4_5

Easy Rust playlist: https://www.youtube.com/watch?v=-lYeJeQ11OI&list=PLfllocyHVgsRwLkTAhG0E-2QxCf-ozBkk

https://oribenshir.github.io/afternoon_rusting/blog/rust-for-oop
Rust for OOP - Series Introduction
This blog is designed to cover topics related to both Rust & C++ languages. This blog has emphasis on strong typing and design choices.

https://stevedonovan.github.io/rust-gentle-intro/object-orientation.html
Introduction to the Rust language, standard library and ecosystem

https://rust-unofficial.github.io/too-many-lists/
Learning Rust With Entirely Too Many Linked Lists

https://oribenshir.github.io/afternoon_rusting/blog/rust-for-oop
Rust for OOP - Series Introduction

https://www.freecodecamp.org/news/how-to-build-a-to-do-app-with-rust/amp/
Rust Programming Language Tutorial – How to Build a To-Do List App

https://teachyourselfcs.com/
All the resources you need to give yourself a world class computer science education

https://learnxinyminutes.com/docs/rust/
Learn Rust in Y Minutes

https://docs.microsoft.com/en-us/learn/paths/rust-first-steps/
Microsoft's Rust tutorials

https://www.ralfj.de/projects/rust-101/part00.html



## Testing

https://knowitlabs.no/rust-2020-testing-4ab3d80112ba

https://archive.fosdem.org/2018/schedule/event/rust_testing_mocking/attachments/slides/2113/export/events/attachments/rust_testing_mocking/slides/2113/testing_in_rust_by_donald_whyte.pdf


## Benching

 Criterion


# Dumping ground

> Everything below here is uncategorised, dumped for later review


