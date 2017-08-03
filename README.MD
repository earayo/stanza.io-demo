# Building bundled/minified for demo version (for AMD, etc)

## Installing stanza.io

Run the following command:
```sh
$ npm install stanza.io
$ npm install -g browserify
```

## Getting Started
1. Find or install a server which supports XMPP over WebSocket (Prosody recommended).
2. Access to `node_modules/stanza.io`
3. Run `npm install`.
4. Run `browserify --standalone XMPP index.js > stanzaio.bundle.js`
5. Copy `stanzaio.bundle.js` in your demo directory.
6. Edit your 'index.html' to replace the loaded script. (i.e `<script src="stanzaio_8.4.3.bundle.js"></script>`)
7. Open in your browser.
8. Enter your connection info, click connect.
9. Use the JS console to play with the XMPP client (`var client`).

## References
- This README.MD is based on [stranza.io](https://github.com/legastero/stanza.io) repo.
