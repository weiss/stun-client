stun
====

A simple STUN client (IPv4-only, UDP-only).

## Requirements

- [Erlang/OTP][erlang] (for building and running).
- [Rebar3][rebar3] (only for building).

## Building

    $ rebar3 escriptize

## Installing

    $ sudo install _build/default/bin/stun /usr/local/bin

## Running

    $ stun stun.conversations.im

[erlang]: https://erlang.org
[rebar3]: https://rebar3.org
