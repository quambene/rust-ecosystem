# The Rust Ecosystem

Categorization of widely-used crates in the Rust ecosystem.

Category                        | Crates
------------------------------- | -------------------------------
error&#160;handling             | [thiserror](https://crates.io/crates/thiserror), [anyhow](https://crates.io/crates/anyhow)
testing                         | [insta](https://crates.io/crates/insta)
performance                     | [cargo-flamegraph](https://crates.io/crates/flamegraph), [inferno](https://crates.io/crates/inferno)
logging                         | [log](https://crates.io/crates/log), [fern](https://crates.io/crates/fern), [log4rs](https://crates.io/crates/log4rs)
tracing                         | [tracing](https://crates.io/crates/tracing), [tracing-subscriber](https://crates.io/crates/tracing-subscriber), [tracing-appender](https://crates.io/crates/tracing-appender), [tracing-test](https://crates.io/crates/tracing-test), [opentelemetry](https://crates.io/crates/opentelemetry)
metrics                         | [metrics](https://crates.io/crates/metrics), [prometheus](https://crates.io/crates/prometheus)
futures                         | [futures::future::Future](https://docs.rs/futures/latest/futures/future/trait.Future.html), [futures::future::FutureExt](https://docs.rs/futures/latest/futures/future/trait.FutureExt.html)
streams                         | [futures::stream::Stream](https://docs.rs/futures/latest/futures/stream/trait.Stream.html), [futures::stream::StreamExt](https://docs.rs/futures/latest/futures/stream/trait.StreamExt.html), [async_std::stream::Stream](https://docs.rs/async-std/latest/async_std/stream/trait.Stream.html), [tokio-stream](https://crates.io/crates/tokio-stream), [tokio_stream::StreamExt](https://docs.rs/tokio-stream/latest/tokio_stream/trait.StreamExt.html), [std::async_iter::AsyncIterator](https://doc.rust-lang.org/std/async_iter/trait.AsyncIterator.html)
channels                        | [std::sync::mpsc](https://doc.rust-lang.org/std/sync/mpsc), [crossbeam::channel](https://docs.rs/crossbeam/latest/crossbeam/channel/index.html) [futures::channel::oneshot::channel](https://docs.rs/futures/latest/futures/channel/oneshot/fn.channel.html), [tokio::sync::mpsc](https://docs.rs/tokio/latest/tokio/sync/mpsc/), [tokio::sync::oneshot](https://docs.rs/tokio/latest/tokio/sync/oneshot/index.html), [tokio::sync::broadcast](https://docs.rs/tokio/latest/tokio/sync/broadcast/index.html), [tokio::sync::watch](https://docs.rs/tokio/latest/tokio/sync/watch/index.html), [async_channel::unbounded](https://docs.rs/async-channel/latest/async_channel/fn.unbounded.html), [async_channel::bounded](https://docs.rs/async-channel/latest/async_channel/fn.bounded.html), [oneshot](https://crates.io/crates/oneshot)
async&#160;runtimes             | [tokio](https://crates.io/crates/tokio)
parallelism                     | [rayon](https://crates.io/crates/rayon), [parallel-stream](https://crates.io/crates/parallel-stream)
HTTP&#160;server                | [actix-web](https://crates.io/crates/actix-web), [hyper](https://crates.io/crates/hyper), [tower](https://crates.io/crates/tower), [axum](https://crates.io/crates/axum)
HTTP&#160;client                | [reqwest](https://crates.io/crates/reqwest)
gRPC                            | [tonic](https://crates.io/crates/tonic), [prost](https://crates.io/crates/prost), [prost-types](https://crates.io/crates/prost-types), [prost-reflect](https://crates.io/crates/prost-reflect), [protobuf](https://crates.io/crates/protobuf), [protobuf-parse](https://crates.io/crates/protobuf-parse)
websockets                      | [tungstenite](https://crates.io/crates/tungstenite), [tokio-tungstenite](https://crates.io/crates/tokio-tungstenite), [actix-web-actors](https://crates.io/crates/actix-web-actors)
database,&#160;sql              | [postgres](https://crates.io/crates/postgres), [tokio-postgres](https://crates.io/crates/tokio-postgres), [sqlx](https://crates.io/crates/sqlx)
database,&#160;ORM              | [diesel](https://crates.io/crates/diesel)
