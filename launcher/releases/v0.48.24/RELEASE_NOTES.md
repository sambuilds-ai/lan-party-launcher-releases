# LAN Party Launcher v0.48.24

## Changes

- Add a desktop game overlay with chat, Game assist and WoW
- Add strong noise suppression to Linux voice (RNNoise after echo cancellation)
- Lock nnnoiseless and its FFT dependencies
- Cancel echo from soundboard effects in strong noise suppression and keep one Pulse connection per call
- Draw themed scrollbars so page scrollbars can't paint over windows and dialogs
- Keep a silent mic silent in strong noise suppression
- Readable desktop UI: icon server controls, clearer session servers, quiet Auto-AFK
- Show and send photos and videos from the desktop chat
- Play chat videos through a blob on Linux and encode captions exactly like the server
- Load desktop chat media only when needed
- Only play chat videos on desktops that can output audio
- Expect the chat-media connect-src entries in the desktop CSP test
- Keep compact GameSpy rows at their old height with the new icon controls
- Bring desktop specs up to date with the readability tokens and chat fixtures
- Split the chat video idle check from the scroll-away release check
- Do not await play() on an autoplaying chat video in the media spec
- Keep a paused chat video on screen instead of resetting it
- Skip only the fixture seek step of the chat video spec in WebKit
- Count only the GameSpy table's icon in the server-controls spec
