# simpler-peer
a little dev playground for [simple-peer](https://github.com/feross/simple-peer)

## demo

[initiator](https://spencercap.github.io/simpler-peer/initiator.html)

[receiver](https://spencercap.github.io/simpler-peer/receiver.html)

## connection flow

1. open `initiator.html`, copy the signal offer
2. open `receiver.html`, paste that signal offer into the text area, then click generate
3. copy the generated signal answer from `receiver.html`
4. paste that signal answer into the text area of `initiator.html`, then click connect
5. enjoy a margarita

in the real world, instead of copying and pasting signal offers and answers, you can use a websocket, some database (like firestore), or even a carrier pigeon 😉 for the signaling.

## version

note, this uses a copy of `simplepeer.min.js` at version `9.6.2`
