<!-- tyhp-readme:start -->
# tyhpdef/symfony-stimulus-bundle

Tyhp type definitions for `symfony/stimulus-bundle` `3.4.0`.

```bash
composer require --dev tyhpdef/symfony-stimulus-bundle:3.4.0
```

This is a metapackage. Composer also installs `tyhpdef/symfony-stimulus-bundle-impl` (type files).
Require **this** name, not `tyhpdef/symfony-stimulus-bundle-impl`.

See https://tyhplang.com.

## Maintain `symfony/stimulus-bundle`? Ship the types yourself

If you are a Packagist maintainer of `symfony/stimulus-bundle`, you can take over these
types.

Copy `_tyhpdef/` from **`tyhpdef/symfony-stimulus-bundle-impl`** (Apache-2.0; keep the `NOTICE`).
Then either:

1. **Bundle** the files in `symfony/stimulus-bundle` and set `extra.tyhp.package` on
   that `composer.json`, plus
   `"replace": { "tyhpdef/symfony-stimulus-bundle": "self.version" }`, or
2. **Publish a sibling** types package under your vendor, versioned with
   `symfony/stimulus-bundle` (same `X.Y.Z`). Set `extra.tyhp.package` there,
   `require` `symfony/stimulus-bundle` with a real constraint,
   `"replace": { "tyhpdef/symfony-stimulus-bundle": "self.version" }`, and set
   `extra.tyhp.tyhpdef` on `symfony/stimulus-bundle` to your sibling’s Composer name.

Ship that to Packagist first, then open an issue:

https://github.com/tyhpproject/tyhp-runtime-src/issues/new?template=tyhpdef-ownership.yml

We verify Packagist ownership and that the types parse and cover the PHP
API, then stop publishing community tags for those versions. We do not
transfer the `tyhpdef/symfony-stimulus-bundle` Packagist name.

Full process: `TYHPDEF_OWNERSHIP.md` in
https://github.com/tyhpproject/tyhp-runtime-src
<!-- tyhp-readme:end -->
