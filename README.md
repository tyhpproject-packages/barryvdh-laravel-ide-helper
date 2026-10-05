<!-- tyhp-readme:start -->
# tyhpdef/barryvdh-laravel-ide-helper

Tyhp type definitions for `barryvdh/laravel-ide-helper` `3.7.0`.

```bash
composer require --dev tyhpdef/barryvdh-laravel-ide-helper:3.7.0
```

This is a metapackage. Composer also installs `tyhpdef/barryvdh-laravel-ide-helper-impl` (type files).
Require **this** name, not `tyhpdef/barryvdh-laravel-ide-helper-impl`.

See https://tyhplang.com.

## Maintain `barryvdh/laravel-ide-helper`? Ship the types yourself

If you are a Packagist maintainer of `barryvdh/laravel-ide-helper`, you can take over these
types.

Copy `_tyhpdef/` from **`tyhpdef/barryvdh-laravel-ide-helper-impl`** (Apache-2.0; keep the `NOTICE`).
Then either:

1. **Bundle** the files in `barryvdh/laravel-ide-helper` and set `extra.tyhp.package` on
   that `composer.json`, plus
   `"replace": { "tyhpdef/barryvdh-laravel-ide-helper": "self.version" }`, or
2. **Publish a sibling** types package under your vendor, versioned with
   `barryvdh/laravel-ide-helper` (same `X.Y.Z`). Set `extra.tyhp.package` there,
   `require` `barryvdh/laravel-ide-helper` with a real constraint,
   `"replace": { "tyhpdef/barryvdh-laravel-ide-helper": "self.version" }`, and set
   `extra.tyhp.tyhpdef` on `barryvdh/laravel-ide-helper` to your sibling’s Composer name.

Ship that to Packagist first, then open an issue:

https://github.com/tyhpproject/tyhp-runtime-src/issues/new?template=tyhpdef-ownership.yml

We verify Packagist ownership and that the types parse and cover the PHP
API, then stop publishing community tags for those versions. We do not
transfer the `tyhpdef/barryvdh-laravel-ide-helper` Packagist name.

Full process: `TYHPDEF_OWNERSHIP.md` in
https://github.com/tyhpproject/tyhp-runtime-src
<!-- tyhp-readme:end -->
