### Utilities, helpers, and hacks from my `PATH`.

Add these to your `PATH` with something like:

```sh
PATH=$(find $BIN_DIR -type d -printf "%p:")$PATH
```

Where `BIN_DIR` is a checkout of this repository.
