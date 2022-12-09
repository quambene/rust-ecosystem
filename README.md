# The Rust Ecosystem

Categorization of widely-used crates in the Rust ecosystem.

Category                        | Crates
------------------------------- | -------------------------------
error&#160;handling                  | [thiserror](https://crates.io/crates/thiserror), [anyhow](https://crates.io/crates/anyhow)
testing                         | [insta](https://crates.io/crates/insta)
logging                         | [log](https://crates.io/crates/log), [fern](https://crates.io/crates/fern), [log4rs](https://crates.io/crates/log4rs)
tracing                         | [tracing](https://crates.io/crates/tracing), [tracing-subscriber](https://crates.io/crates/tracing-subscriber), [tracing-appender](https://crates.io/crates/tracing-appender), [tracing-test](https://crates.io/crates/tracing-test), [opentelemetry](https://crates.io/crates/opentelemetry)
metrics                         | [metrics](https://crates.io/crates/metrics), [prometheus](https://crates.io/crates/prometheus)
futures                         | [futures::future::Future](https://docs.rs/futures/latest/futures/future/trait.Future.html), [futures::future::FutureExt](https://docs.rs/futures/latest/futures/future/trait.FutureExt.html)
streams                         | [futures::stream::Stream](https://docs.rs/futures/latest/futures/stream/trait.Stream.html), [futures::stream::StreamExt](https://docs.rs/futures/latest/futures/stream/trait.StreamExt.html), [async_std::stream::Stream](https://docs.rs/async-std/latest/async_std/stream/trait.Stream.html), [tokio-stream](https://crates.io/crates/tokio-stream), [tokio_stream::StreamExt](https://docs.rs/tokio-stream/latest/tokio_stream/trait.StreamExt.html), [std::async_iter::AsyncIterator](https://doc.rust-lang.org/std/async_iter/trait.AsyncIterator.html)
HTTP&#160;server                     | [actix-web](https://crates.io/crates/actix-web), [hyper](https://crates.io/crates/hyper), [tower](https://crates.io/crates/tower), [axum](https://crates.io/crates/axum)
HTTP&#160;client                     | [reqwest](https://crates.io/crates/reqwest)
gRPC                            | [tonic](https://crates.io/crates/tonic), [prost](https://crates.io/crates/prost), [prost-types](https://crates.io/crates/prost-types), [prost-reflect](https://crates.io/crates/prost-reflect), [protobuf](https://crates.io/crates/protobuf), [protobuf-parse](https://crates.io/crates/protobuf-parse)
websockets                      | [tungstenite](https://crates.io/crates/tungstenite), [tokio-tungstenite](https://crates.io/crates/tokio-tungstenite), [actix-web-actors](https://crates.io/crates/actix-web-actors)
