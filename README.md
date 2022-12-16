# elephant-forwarder
URL obfuscation for posting Mastodon links on Twitter.

## Usage
Prepend `https://mvernacc.github.io/elephant-forwarder/?link=` to your Mastodon link, and replace at least one period `.` in the Mastodon URL with a comma `,` e.g. https://mvernacc.github.io/elephant-forwarder/?link=hachyderm,io.

This will take the viewer to an intermediate page, with a link to continue to Mastodon (As of 2022-12-16 15:00Z, Twitter would block a link with an immediate re-direct, hence the intermediate page).

