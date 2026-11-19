# Night Work

Working title. A browser prototype of a real-time, first-person fantasy heist game. Thief, Warrior and Wizard each clear their own lock on a vault door. Do your part, then repost the job for the next specialist, or play it live with up to three friends.

**Play:** open the GitHub Pages site for this repository. Nothing to install and no accounts.

## Co-op
1. Type your name, tick "Host the next job I start as live co-op", and press Play on a job.
2. Send friends the page address and the four-letter room code at the top of the screen.
3. They choose "Join a friend", type the code and pick a class.

Players connect browser to browser (WebRTC via [PeerJS](https://peerjs.com)); the free public PeerJS server only introduces them. The host's browser runs the guards, so keep the host's tab in front. Some strict office or school networks block these connections.

## Controls
WASD move, mouse looks (click the view to capture it). Shift runs, C crouches, left click strikes, right click uses ability 1, E uses what you aim at, 1/2/3 abilities, Esc pauses.

## Files
- `index.html`: the whole game.
- `three.min.js` (three.js r128, MIT) and `peerjs.min.js` (PeerJS 1.5.4, MIT): vendored libraries.
