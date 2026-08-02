# novus-http

HTTP client and server primitives built on net.

A library for the [Novus](https://github.com/MJDaws0n/Novus) language, installable
via [Nox](https://github.com/MJDaws0n/Nox).

## Install

```sh
nox pull http
```

## Documentation

See [`docs.md`](docs.md) for the full API reference.

## Import

```novus
import lib/http http;
```

`http` installs and imports its `std`, `net`, and `file_io` dependencies. An
application only needs to import `lib/http` to use the complete API, including
`http_serve_file`.

## Supported targets

- macOS arm64
- Linux x86-64
- Linux arm64
