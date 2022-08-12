This is a (hopefully temporary) fork of [sodiumoxide](https://github.com/sodiumoxide/sodiumoxide) (no relation).

We use [thrussh](https://crates.io/crates/thrussh) for integration tests in [the Oxide control plane](https://github.com/oxidecomputer/omicron), which has a dependency on libsodium-sys. We maintain this fork so that there is a version of libsodium-sys that can build for illumos.

If our patch to libsodium-sys/build.rs is accepted upstream we can delete our fork.

(Oxide internal: see RFD 211 for maintenance steps.)
