# Sourcing · The Second Look

Phone app for logging sourcing hauls and tracking buy goals. This repository holds only the app's screens and math.
It contains no business data and no keys: the data lives in a private Google Sheet, and each phone stores its own key at setup.

## Listing Cam (`camera/`)

Camera for listing photos: autofocus, a Kelvin white-balance dial with presets, gray-card color correction, a brightness dial, a grid, and square photos by default (3:4 vertical under More).
Built for one hand: every control sits in the bottom third, with a left-hand option. Photos are always vertical (3:4) and the screen never turns, whichever way the phone is held.
The gray card sets color and brightness (card = middle gray). **Lock** watches a spot of background and undoes the phone's own brightness and color changes, so every item comes out the same.
Shoot mode (on automatically after Lock) turns the whole bottom area into the shutter and hides every other button; hold the top button to get controls back.
Tap the thumbnail to review shots full screen: double-tap or pinch to zoom and check focus, swipe between shots, save or delete.
"Fix a photo" applies the same gray-card and Kelvin correction to a photo taken in another app.
Settings, including the gray-card reading, are remembered on the phone. With Auto-save on, the save sheet opens after each shot (tap Save Image); with it off, photos collect in the thumbnail and save together. iPhone web apps cannot write to Photos without that tap.
