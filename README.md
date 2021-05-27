testnet.ergo.chat
=================

These are config files for the [Ergo testnet](https://testnet.ergo.chat). They provide a "worked example" of how to configure Ergo as a systemd service, with nginx and Kiwi IRC.

Installation instructions for most config files are described in comments in the config files. The exception is Kiwi's config.json. To install Kiwi in a standard nginx configuration:

1. Obtain a [release build of Kiwi](https://github.com/kiwiirc/kiwiirc/releases) and extract it into /var/www/html
2. Replace `static/config.json` with your own config.json file. You must replace the `websocket` key with the address of your own server.
