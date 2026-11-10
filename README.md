# curl

curl 8.23.0: the curl command and libcurl (HTTP and HTTPS; 64-bit tOS)

A package for [tOS](https://github.com/Artfical/tOS), installed with `tpkg`:

```
sudo tpkg install curl
```

| | |
|---|---|
| Version | 8.23.0 |
| Licence | curl |
| Upstream | https://curl.se |
| Needs | [`openssl`](https://github.com/Artfical/tpkg-openssl), [`zlib`](https://github.com/Artfical/tpkg-zlib), [`ca-certificates`](https://github.com/Artfical/tpkg-ca-certificates) |
| Needs tOS build | 608 or newer |
| Size | 443106 bytes (993168 unpacked) |
| SHA-256 of the `.tpkg` | `0be7f13d8412749166b716f2e57aa06537456df647283a30a296904f504cdc8a` |

## Commands it adds

| Command | Runs |
|---|---|
| `curl` | `bin/curl` |

## Download

The package file (`curl-8.23.0.tpkg`) and the sources it was built from are the assets of the
[v8.23.0 release](https://github.com/Artfical/tpkg-curl/releases/tag/v8.23.0).
Git holds only the text: `meta.json`, the licences and `NOTICE.txt` (how it was built and what was changed).

Sources in the release:
- (none: see the upstream page above)

Check a download: `sha256sum curl-8.23.0.tpkg` must give the hash above.

## Signatures

Packages are signed by Artfical's package server (Ed25519) and tOS checks the signature before it installs one.
The signature is made when the server hands a package out, so it is not kept here, and the signing key is never published.
`tpkg install` is the supported way to install; a `.tpkg` taken from here has the hash above but not the server's signature.

## Licence

The package is made of other people's software, under their licences: curl. The licence texts are in this
repository (`LICENSE*`, `UNLICENSE`), and `NOTICE.txt` says how it was built. The sources above are the
corresponding source. `meta.json` and this README are free to copy.

Package problems (build, files, versions): open an issue here. Problems in the software itself belong upstream.
Security reports: see [SECURITY.md](https://github.com/Artfical/tOS/blob/main/SECURITY.md).
