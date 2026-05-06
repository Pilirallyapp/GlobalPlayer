# Global Player Automator 🚗📻

This project contains the automation logic to launch **Classic FM** on the **Global Player** Android app hands-free while driving.

## Goal
To bypass manual navigation and use a voice command ("Hey Google") to trigger a specific station directly via Android Intents.

## Automation Details
- **App:** Global Player
- **Station:** Classic FM
- **Action:** `android.intent.action.VIEW`
- **Data URI:** `globalplayer://live-radio/classicfm`
- **Package:** `com.global.player`

## How to Set Up on Mobile
1. Install **MacroDroid** or **Tasker** on your Android device.
2. Create a new Macro triggered by the phrase "Play Classic FM".
3. Add a "Send Intent" action using the parameters listed above.

## Notes
- Ensure Global Player is installed and you are logged in.
- This bypasses the need to manually "hit" the icon on the screen.
- Maintained by Pantelis
