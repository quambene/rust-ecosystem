# The Rust Ecosystem

Categorization of (more or less) widely used crates in the Rust ecosystem.

Category                        | Crates
------------------------------- | -------------------------------
error&#160;handling             | [thiserror](https://crates.io/crates/thiserror), [anyhow](https://crates.io/crates/anyhow)
testing                         | [assert_matches](https://crates.io/crates/assert_matches), [insta](https://crates.io/crates/insta), [tokio-test](https://crates.io/crates/tokio-test), [tracing-test](https://crates.io/crates/tracing-test), [rstest](https://crates.io/crates/rstest), [test-case](https://crates.io/crates/test-case)
code coverage                   | [cargo-tarpaulin](https://crates.io/crates/cargo-tarpaulin), [cargo-llvm-cov](https://crates.io/crates/cargo-llvm-cov)
performance                     | [cargo-flamegraph](https://crates.io/crates/flamegraph), [inferno](https://crates.io/crates/inferno), [criterion](https://crates.io/crates/criterion)
logging                         | [log](https://crates.io/crates/log), [fern](https://crates.io/crates/fern), [log4rs](https://crates.io/crates/log4rs)
tracing                         | [tracing](https://crates.io/crates/tracing), [tracing-subscriber](https://crates.io/crates/tracing-subscriber), [tracing-appender](https://crates.io/crates/tracing-appender), [tracing-test](https://crates.io/crates/tracing-test)
metrics                         | [metrics](https://crates.io/crates/metrics), [prometheus](https://crates.io/crates/prometheus), [opentelemetry](https://crates.io/crates/opentelemetry), [tracing-opentelemetry](https://crates.io/crates/tracing-opentelemetry), [opentelemetry-datadog](https://crates.io/crates/opentelemetry-datadog), [statsd](https://crates.io/crates/statsd), [cadence](https://crates.io/crates/cadence)
decimal/rational&#160;numbers   | [rust_decimal](https://crates.io/crates/rust_decimal), [num-rational](https://crates.io/crates/num-rational)
time                            | [std::time](https://doc.rust-lang.org/std/time/index.html), [time](https://crates.io/crates/time), [chrono](https://crates.io/crates/chrono)
email                           | [lettre](https://crates.io/crates/lettre), [rusoto_ses](https://crates.io/crates/rusoto_ses), [rusoto_credential](https://github.com/quambene/pigeon-rs/blob/master/Cargo.toml)
serialization/deserialization   | [serde](https://crates.io/crates/serde), [serde_json](https://crates.io/crates/serde_json), [serde_path_to_error](https://crates.io/crates/serde_path_to_error), [serde_yaml](https://crates.io/crates/serde_yaml), [rkyv](https://crates.io/crates/rkyv)
encoding/decoding               | [base64](https://crates.io/crates/base64)
parsing                         | [csv](https://crates.io/crates/csv)
xml                             | [xml-rs](https://crates.io/crates/xml-rs), [quick-xml](https://crates.io/crates/quick-xml), [xmlparser](https://crates.io/crates/xmlparser), [roxmltree](https://crates.io/crates/roxmltree), [xot](https://crates.io/crates/xot)
encryption                      | [ring](https://crates.io/crates/ring), [rustls](https://crates.io/crates/rustls)
authentication,&#160;JWT        | [jsonwebtoken](https://crates.io/crates/jsonwebtoken)
futures                         | [futures::future::Future](https://docs.rs/futures/latest/futures/future/trait.Future.html), [futures::future::FutureExt](https://docs.rs/futures/latest/futures/future/trait.FutureExt.html)
streams                         | [futures::stream::Stream](https://docs.rs/futures/latest/futures/stream/trait.Stream.html), [futures::stream::StreamExt](https://docs.rs/futures/latest/futures/stream/trait.StreamExt.html), [async_std::stream::Stream](https://docs.rs/async-std/latest/async_std/stream/trait.Stream.html), [tokio-stream](https://crates.io/crates/tokio-stream), [tokio_stream::StreamExt](https://docs.rs/tokio-stream/latest/tokio_stream/trait.StreamExt.html), [std::async_iter::AsyncIterator](https://doc.rust-lang.org/std/async_iter/trait.AsyncIterator.html)
channels                        | [std::sync::mpsc](https://doc.rust-lang.org/std/sync/mpsc), [crossbeam::channel](https://docs.rs/crossbeam/latest/crossbeam/channel/index.html) [futures::channel::oneshot](https://docs.rs/futures/latest/futures/channel/oneshot/index.html), [tokio::sync::mpsc](https://docs.rs/tokio/latest/tokio/sync/mpsc/), [tokio::sync::oneshot](https://docs.rs/tokio/latest/tokio/sync/oneshot/index.html), [tokio::sync::broadcast](https://docs.rs/tokio/latest/tokio/sync/broadcast/index.html), [tokio::sync::watch](https://docs.rs/tokio/latest/tokio/sync/watch/index.html), [async_channel::unbounded](https://docs.rs/async-channel/latest/async_channel/fn.unbounded.html), [async_channel::bounded](https://docs.rs/async-channel/latest/async_channel/fn.bounded.html), [oneshot](https://crates.io/crates/oneshot)
async&#160;runtime              | [tokio](https://crates.io/crates/tokio)
concurrency                     | [dashmap](https://crates.io/crates/dashmap)
parallelism                     | [rayon](https://crates.io/crates/rayon), [parallel-stream](https://crates.io/crates/parallel-stream)
HTTP&#160;client                | [reqwest](https://crates.io/crates/reqwest), [ureq](https://crates.io/crates/ureq), [isahc](https://crates.io/crates/isahc)
HTTP&#160;server                | [actix-web](https://crates.io/crates/actix-web), [hyper](https://crates.io/crates/hyper), [tower](https://crates.io/crates/tower), [axum](https://crates.io/crates/axum), [rocket](https://crates.io/crates/rocket), [tide](https://crates.io/crates/tide)
gRPC                            | [tonic](https://crates.io/crates/tonic), [prost](https://crates.io/crates/prost), [prost-types](https://crates.io/crates/prost-types), [prost-reflect](https://crates.io/crates/prost-reflect), [protobuf](https://crates.io/crates/protobuf), [protobuf-parse](https://crates.io/crates/protobuf-parse)
websockets                      | [tungstenite](https://crates.io/crates/tungstenite), [tokio-tungstenite](https://crates.io/crates/tokio-tungstenite), [actix-web-actors](https://crates.io/crates/actix-web-actors)
message queue                   | [celery](https://crates.io/crates/celery), [message-io](https://crates.io/crates/message-io)
database,&#160;SQL              | [postgres](https://crates.io/crates/postgres), [tokio-postgres](https://crates.io/crates/tokio-postgres), [sqlx](https://crates.io/crates/sqlx), [connectorx](https://crates.io/crates/connectorx)
database,&#160;ORM              | [diesel](https://crates.io/crates/diesel)
pool                            | [deadpool](https://crates.io/crates/deadpool)
data&#160;processing            | [arrow](https://crates.io/crates/arrow), [arrow2](https://crates.io/crates/arrow2), [polars](https://crates.io/crates/polars)
inversion&#160;of&#160;control  | [inject](https://crates.io/crates/inject)
CLI                             | [clap](https://crates.io/crates/clap), [structopt](https://crates.io/crates/structopt), [quicli](https://crates.io/crates/quicli), [ergo](https://crates.io/crates/ergo)
scripting                       | [cargo-script](https://crates.io/crates/cargo-script), [dyon](https://crates.io/crates/dyon), [rustscript](https://github.com/faern/rustscript), [ion](https://github.com/redox-os/ion), [runner](https://crates.io/crates/runner), [mlua](https://crates.io/crates/mlua), [rhai](https://crates.io/crates/rhai)
GUI                             | [egui](https://crates.io/crates/egui), [edom](https://crates.io/crates/edom), [tauri](https://crates.io/crates/tauri), [druid](https://crates.io/crates/druid), [iced](https://crates.io/crates/iced), [kas](https://crates.io/crates/kas), [dioxus](https://crates.io/crates/dioxus), [yew](https://crates.io/crates/yew), [leptos](https://crates.io/crates/leptos), [slint](https://crates.io/crates/slint)
embedded                        | [cortex-m](https://crates.io/crates/cortex-m), [cortex-m-rt](https://crates.io/crates/cortex-m-rt), [cortex-m-semihosting](https://crates.io/crates/cortex-m-semihosting)
wasm                            | [wasm-bindgen](https://crates.io/crates/wasm-bindgen), [wasm-bindgen-cli](https://crates.io/crates/wasm-bindgen-cli)
compiler                        | [ferrocene](https://crates.io/crates/ferrocene)
l10n, i18n                      | [rocket_i18n](https://crates.io/crates/rocket_i18n)
