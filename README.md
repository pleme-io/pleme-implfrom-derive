# pleme-implfrom-derive

Newtype-bidirectional From: impl From<Inner> for Wrapper + impl From<Wrapper> for Inner. The single highest-leverage newtype derive across pleme-io (~840 hand-rolled blocks in the corpus).

[![Build](https://github.com/pleme-io/pleme-implfrom-derive/actions/workflows/auto-release.yml/badge.svg)](#)
[![crates.io](https://img.shields.io/crates/v/pleme-implfrom-derive.svg)](https://crates.io/crates/pleme-implfrom-derive)

## Install

```toml
[dependencies]
pleme-implfrom-derive = "*"
```

## Generation

This crate is mechanically emitted by [`tatara-rust-ast`](https://github.com/pleme-io/tatara-rust-ast). The author surface is a typed `(defmacro …)` Spec — the proc-macro implementation, tests, Nix flake, caixa wrapper, and CI workflow are all generated. See the catalog at `catalog.json` in the parent registry.
