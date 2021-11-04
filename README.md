# test-multi-opam-monorepo

Use this repository to test opam-monorepo in a multi-opam project

## Layout

This repo defines two packages at the root: `a` and `b`. It also defines another
package in `c` in the `c/` folder.

The dependencies between those packages can be defined as `a -> b -> c` where
`->` reads as "depends on".
