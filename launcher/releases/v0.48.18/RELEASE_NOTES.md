# LAN Party Launcher v0.48.18

## Changes

- Add the desktop half of the admin Claude assistant, kept across look switches
- Keep zod out of the desktop assistant and fix history, refresh and failure handling
- Compare the retried chat requests by value
- Refresh only the event an assistant change touched, keep focus, and show real Apply errors
- Let End toggle mute while a LAN Party game is running
- Track modifiers in event order, let LAN Party veto typing presses, and own presses by press
- Keep the in-game mute unit tests from hanging on a slow machine
- Name the assistant's message box and keep Send off for an empty cleaned draft
- Treat stale interface options as echoes and re-read focus for the typing veto
- Wire the in-game mute key into the tabbed voice settings
- Keep the in-game mute key out of focused tab bars and fix the dock's keybind caption
- Style the Claude opener like the other header buttons and let Settings search find the in-game mute switch
