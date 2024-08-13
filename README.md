xandkar
===============================================================================

On a quest for **fault tolerant** systems that refuse to die.

Weapons of choice: Rust, OCaml, and Erlang.

The coolest thing I've worked on was the late
[Helium blockchain](https://github.com/helium/blockchain-core).

`lib`
-------------------------------------------------------------------------------

- [`beam_stats`](https://github.com/xandkar/beam_stats):
  collect detailed Erlang VM metrics and send to arbitrary, pluggable backends
- [`hope`](https://github.com/xandkar/hope):
  _Higher Order Programming in Erlang_ - a living experiment with uniform,
  composable abstractions
- [`stream`](https://github.com/xandkar/erlang-stream):
  streams with parallel processing, lazy filtering and
  [optimal random sampling](https://en.wikipedia.org/wiki/Reservoir_sampling)
- [`contract`](https://github.com/xandkar/erlang-contract):
  an embedded [Design by contract](https://en.wikipedia.org/wiki/Design_by_contract)
  DSL
- [`x-plane-data`](https://github.com/xandkar/erlang-x-plane-data):
  X-Plane UDP data parser for Erlang
- [`google-authenticator-uri`](https://github.com/xandkar/erlang-google-authenticator-uri):
  Google Authenticator URI constructor
- [RFC 4226 - HMAC-Based One-Time Password](https://github.com/xandkar/erlang-hotp)
- [RFC 6238 - Time-Based One-Time Password](https://github.com/xandkar/erlang-totp)
- [RFC 5849 - OAuth 1 Protocol](https://github.com/xandkar/oauth1_core):
  server and storage independent library, supports eventual consistency via
  [state-based CRDTs](https://en.wikipedia.org/wiki/Conflict-free_replicated_data_type#State-based_CRDTs)
- [`crdt`](https://github.com/xandkar/erlang-crdt):
  select, app-level, state-based CRDTs (used above)
- [`merkler`](https://github.com/xandkar/merkler):
  a Merkle tree implementation for Erlang

Of which [`beam_stats`](https://github.com/xandkar/beam_stats) and
[`hope`](https://github.com/xandkar/hope) are my go-to.

`bin`
-------------------------------------------------------------------------------

- [`ma`](https://github.com/xandkar/ma):
  mail archivist - pull from N IMAP accounts into 1 SQLite database
- [`phorg`](https://github.com/xandkar/phorg):
  idempotent photo/video file organizer (EXIF + hash --> filepath)
- [`barista`](https://github.com/xandkar/barista):
  concurrent status bar with feed process monitoring, expirations, remote
  control and live reconfiguration (successor to `pista`)
- [`stamon`](https://github.com/xandkar/stamon):
  collection of various status data collectors/aggregators
- [`pista`](https://github.com/xandkar/pista):
  event loop over N FIFOs, reading line streams and writing into N segments of
  your status buffer, with a TTL per segment
- [`pistactl`](https://github.com/xandkar/pistactl):
  being inspired by ii, `pista` is minimal and calls for a convenience layer in
  practice, this is it
- [`gg`](https://github.com/xandkar/gg):
  git of gits - discover, catalogue and compare all your git repos
- [`dups`](https://github.com/xandkar/dups): duplicate file finder
- [`probe-me`](https://github.com/xandkar/probe-me):
  TCP port probing microservice for lightweight perimeter monitoring
- [`git-analysis`](https://github.com/xandkar/git-analysis):
  exploratory analysis of a Git repository
- [`dropbox-conflicts`](https://github.com/xandkar/dropbox-conflicts):
  build a tree of conflict dependencies in your Droppbox directory
- [`tt`](https://github.com/xandkar/tt):
  client and a crawler of twtxt (a P2P microblogging network

`edu`
-------------------------------------------------------------------------------

- [`tiger.ml`](https://github.com/xandkar/tiger.ml): Tiger front end in OCaml
- [`numerals`](https://github.com/xandkar/numerals): how do they even work?
- [`ShilovLinearAlgebra`](https://github.com/xandkar/ShilovLinearAlgebra):
  concrete tests for (some) theorems presented in Shilov's Linear Algebra book
- [Evolutionary Computation Exercises](https://github.com/xandkar/evolutionary-problems)

`env`
-------------------------------------------------------------------------------

BTW, I use [Void](https://voidlinux.org/) with
[dwm](https://github.com/xandkar/dwm), [st](https://github.com/xandkar/st),
and a [home](https://github.com/xandkar/khome/)-grown
[status](https://github.com/xandkar/stamon)
[bar](https://github.com/xandkar/barista).

[nvim](https://neovim.io/) with [CoC](https://github.com/neoclide/coc.nvim/).

I gave VSCode and JetBrains an honest try - they're very nice, but feel like
major degradations of ergonomics from my whole desktop being an integrated
development environment.
