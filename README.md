# VS Code Extension for `woke`

Run [`woke`](https://github.com/get-woke/woke) in VS Code

## Features

All the awesome features of `woke`, within VS Code!

Animations coming soon!

## Requirements

You must have [`woke`](https://github.com/get-woke/woke#installation) installed to use this extension. Requires `v0.2.0` or better.

## Extension Settings

This extension contributes the following settings:

* `woke.enable`: enable/disable this extension
* `woke.executablePath`: set the path to the `woke` executable. By default, it will use `woke` that is found in your PATH. Set this value if you install `woke` elsewhere.
* `woke.run`: run `woke` on save, on type, or manually. Note that "on type" does not currently have any debouncing.
* `woke.customArgs`: Additional arguments to run `woke` with (See <https://github.com/get-woke/woke#usage>)
* `woke.disableVersionCheck`: Whether to disable woke binary version check, which prompt for updating when outdated version found (default false).
