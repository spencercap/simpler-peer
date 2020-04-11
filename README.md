# simpler-peer
how simple is simple-peer ?

## answer: pretty simple.
you just gotta do the signaling yourself.

## demo: connecting

note, the code in this branch is concise but the `basic-connection-2-files` branch better exemplifies the connection handshake as it doesnt reuse the same text area.

1. open `index.html#initiator`, copy the signal offer
2. open `index.html` and paste that signal offer into the text area, click submit
3. copy the generated signal answer
4. paste that signal answer into the text area on `index.html#initiator`
5. bewm

in the real world, instead of copying and pasting signal offers and answers, you can use a websocket, some database (like firestore), or even a carrier pigeon 😉 for the signaling.

## version

note, this uses a copy of `simplepeer.min.js` at version `9.6.2`
