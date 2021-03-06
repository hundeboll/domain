# domain

[![Travis Build Status](https://travis-ci.org/NLnetLabs/domain-core.svg?branch=master)](https://travis-ci.org/NLnetLabs/domain-core)
[![AppVeyor Build
Status](https://ci.appveyor.com/api/projects/status/github/NLnetLabs/domain-core?svg=true)](https://ci.appveyor.com/project/partim/domain-core)

A family of crates (eventually) providing a comprehensive DNS library for
Rust. Currently, it consists of the following individual crates:

* [domain], containing the core data structures and functionality for
  handling DNS data, DNSSEC signing and validation, and more.

  [![Current](https://img.shields.io/crates/v/domain.svg)](https://crates.io/crates/domain)
  [![Documentation](https://docs.rs/domain/badge.svg)](https://docs.rs/domain)

* [domain-resolv], an asynchronous stub resolver.

  [![Current](https://img.shields.io/crates/v/domain-resolv.svg)](https://crates.io/crates/domain-resolv)
  [![Documentation](https://docs.rs/domain-resolv/badge.svg)](https://docs.rs/domain-resolv)

Note that `domain-resolv` will be merged into `domain` once async
functions are available in no-std crates.

[domain]: https://github.com/NLnetLabs/domain-core/tree/master/domain
[domain-resolv]: https://github.com/NLnetLabs/domain-core/tree/master/domain-resolv


## What’s Next?

We have collected our plans for the next steps in development of these
crates in the [Development Roadmap].

For ideas that would benefit from some user feedback, we are creating
issues with the [discuss] label.

If you have ideas, requests, or proposals, don’t hesitate to open issues.

[Development Roadmap]: https://github.com/NLnetLabs/domain/projects/1
[discuss]: https://github.com/NLnetLabs/domain/labels/discuss


## Contributing

If you have comments, proposed changes, or would like to contribute,
please open an issue.


## Licensing

All domain crates are distributed under the terms of the BSD-3-clause
license. See the LICENSE files in the individual crates for details.

