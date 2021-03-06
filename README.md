

# Babel Legacy Decorator plugin

This is a plugin for Babel 6 that is meant to replicate the old decorator behavior from
Babel 5 in order to allow people to more easily transition to Babel 6 without needing to
be blocked on updates to the decorator proposal or for Babel to re-implement it.


## Best Effort

Beware, this plugin is a best effort to maintain feature parity with Babel 5, but there
are slight differences if you were relied on side-effects between decorators in some
cases.

## Limitations

* Currently this implementation discards changes to `enumerable`, `configurable` and `writable`
when decorating class properties.
* Currently decorating static class properties is unsupported. Support will be added shortly.

## License

MIT (c) 2015
