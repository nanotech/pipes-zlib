# Version 0.4.1

* Added `Pipes.GZip` module.


# Version 0.4.0.1

* Bump upper bound dependency on `transformers`.


# Version 0.4.0

* Backwards incompatible API. `compress` and `decompress` are now
  functions of `Producer'`s as they need to perform actions at the
  beginning and end of input. (Issue #3)


# Version 0.3.1

* Dependency upper bounds.


# Version 0.3.0

* Upgraded to work with pipes-4.0.0, creating a new backwards
  incompatible API.

* Generalize base `IO` monad to `MonadIO`.


# Version 0.2.0.0

* New backwards incompatible API.

* Based on pipes-3.3 and zlib-bindings.


# Up to version 0.1.0

* Based on pipes-core and zlib-bindings.
