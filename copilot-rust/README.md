[![Build Status](https://travis-ci.com/Copilot-Language/copilot.svg?branch=master)](https://app.travis-ci.com/github/Copilot-Language/copilot)

Copilot is a runtime verification framework written in Haskell. It allows the
user to write programs in a simple but powerful way using a stream-based
approach.

Programs can be interpreted for testing, or translated Rust code to be
incorporated in a project, or as a standalone application. The Rust backend
ensures us that the output is constant in memory and time, making it suitable
for systems with hard realtime requirements.

This project is currently an attempt at developing a proof-of-concept rust
backend for Copilot.

**This project is ongoing and community driven**

- Please use the discussions on github to communicate with other community
members.

- Please make sure you read [the welcoming
  message](https://github.com/Copilot-Language/copilot-rust/discussions/1),
which sets the tone for how interaction should happen.

- Please do not upload any packages to hackage for this backend yet. This is a
  proof of concept; we'll upload the package once we decide it's ready for
  users.

## License
Copilot is distributed under the BSD-3-Clause license, which can be found
[here](https://raw.githubusercontent.com/Copilot-Language/copilot/master/copilot-rust/LICENSE).
