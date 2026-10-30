# Third-party source code

The direct-install GhostPilot app (`GhostPilot-full-*.apk`) bundles these programs, unmodified from
Termux packages, for its built-in Linux. This folder holds their complete corresponding source, as
their licenses require.

| Program | Version | License | Source here | Upstream |
| --- | --- | --- | --- | --- |
| proot (+ loader) | 5.1.107.101 | GPL-2.0 | `proot-5.1.107.101.zip` | https://github.com/termux/proot |
| talloc (libtalloc) | 2.5.0 | LGPL-3.0-or-later | `talloc-2.5.0.tar.gz` | https://talloc.samba.org |
| libandroid-shmem | 0.7 | BSD-3-Clause | `libandroid-shmem-0.7.tar.gz` | https://github.com/termux/libandroid-shmem |

`termux-build-recipes/` has the Termux `build.sh` files that build them (packages proot, libtalloc,
libandroid-shmem in https://github.com/termux/termux-packages).

SHA-256 (matching the Termux recipes):

```
a66743f50c7b0bac1913b83bf55e139d679c80a0ca2808eec76432a65640017f  proot-5.1.107.101.zip
912afa237510ae542a7733998eb18a12bcda35ab6729c8e2ddb43e8d0ebab007  talloc-2.5.0.tar.gz
1e5ff8459bc0a8c229dd8a94b27d119987e09ef3414331c2b5ebfff20b98e867  libandroid-shmem-0.7.tar.gz
```

Questions or a copy on request: imoneleft@naver.com
