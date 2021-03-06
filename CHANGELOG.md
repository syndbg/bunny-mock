## v1.2.1

* [#5](https://github.com/arempe93/bunny-mock/pull/5): Fixes `routing_key` being modified when delivering in a topic exchange - [@austinmoore](https://github.com/austinmoore)

## v1.2.0

* Adds `with_channel` functionality to `BunnyMock::Session`
* Renames `BunnyMock::Exchange#has_binding?` to `BunnyMock::Exchange#routes_to?`
* Adds `Bunny` as a dependency to use its exceptions

## v1.1.0

* Moves queue and exchange storage to `BunnyMock::Session`
* Adds `queue_exists?` and `exchange_exists?` methods to `BunnyMock::Session`

## v1.0.0

First stable release!
