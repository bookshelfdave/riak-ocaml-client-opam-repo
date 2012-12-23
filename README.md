This is an OPAM repository for development branches of the
[riak-ocaml-client](https://github.com/metadave/riak-ocaml-client).

[OPAM](http://opam.ocamlpro.com/) is a package manager for OCaml.

Stable riak-ocaml-client and riak-pb versions will be submitted to the official
[OPAM repository](https://github.com/OCamlPro/opam-repository) when they reach v1.0.

## Installing using OPAM

1. Add this repository as a _remote_

```
opam remote -add riak git@github.com:metadave/riak-ocaml-client-opam-repo.git
```

2. After that, run

```
opam install riak-pb
  and/or
opam install riak
```

This command will install the latest development version of the riak-ocaml-client for OCaml.
