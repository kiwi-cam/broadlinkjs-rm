# Broadlink RM

## Introduction
This module allows you to control the IR and RF interfaces within Broadlink RM devices.

## Like this module?

If you like this module and want to show your support then please star the Github repo, or better yet; buy me a drink using [Paypal](https://paypal.me/kiwicamRM).

Thank you, sincerely!

## Events

| event | description |
| --- | --- |
| `deviceReady` | Emitted with the `Device` once it has authenticated and is ready to accept commands. Also emitted again after a device re-authenticates. |
| `deviceMoved` | Emitted with the `Device` when a known device answers discovery from a different address. `device.host.address` has already been updated and the device is re-authenticating. Useful for consumers that index devices by address. |

## Thanks
Thanks to @momodalo (https://github.com/momodalo/broadlinkjs/), @lprhodes (https://github.com/lprhodes/broadlinkjs-rm/) and @mjg59 (https://github.com/mjg59/python-broadlink/) work to which this is largely based on.
