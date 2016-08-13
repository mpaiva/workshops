#Proto.io

### Pro
1. Build on browser
2. Test on Device (iOS and Android)
3. Large gestural support library
4. Screens, States and Variables
5. Drag & Drop interface
6. Design and Prototype
7. Dropbox Sync
8. Offline Mode
9. **Usability Testing** 
	- usertesting.com (recruit users)
	- lookback.io (your own users) 
10. 

### Con
1. Slow performance for deep-level prototypes
2. Limitted trial
3. Sketch plugin is not helpful


### Overview
1. Dashboard
2. Preview
3. Editor
	- Top - Patterns
	- Top - Grids
	- Top - Addons (Usability)
	- Top - Screens
	- Top - Assets (Dropbox Sync)
	- Top - Fonts (Webfonts)
	- Top - Share (Usability)
	- Top - Download
	- Top - Save and Preview
	- Left - Screen Panel
	- Left - Layers Panel
	- Bottom - States Panel
	- Right - Libraries Panel
	- Right - Assets Panel	 

### Live Demo
Open this on your browser or phone: 
#**[pr.to/5QK7H4](https://pr.to/5QK7H4/)**

### Step 01 - Exporting Importing Assets
1. Sketch - Export design assets
2. Proto.io - Create a New Project
3. Assets Manager and Dropbox Sync
3. Upload design assets to Proto.io
4. Review `Screens` (start screen with **dot**)
5. Review `Layers`

### Step 02 - Screen Interactions
1. Rename `Screen 1` to `Splash Home`
2. Create `New Screen` called `Splash Loading`
3. Add `Screen Interaction`
	- Title: to-home
	- Trigger: `Screen before show`
	- Action: `Go to Screen`
	- Screen: `Splash Home`
	- Transition: `Fade`
	- Duration: `1000`
	- Easing: `Ease out`
	- Delay: `1000`
4. Preview

### Step 03 - State Interactions
1. Under Libraries, add `iOS 9 Progress bar` onto `Splash Loading` screen
2. Rename it to `loading`
3. Align to center 
4. review layer properties
	- w: `190`
	- Color/Fill
	- Progress: `0%`
5. Create `New Screen State`
6. Select `State 2`
7. Select `loading` layer
8. change `progress` property to `100%`
9. Select `State Transactions`
10. Create `New State Transition`
11. Press the Play button to preview
12. Change transition time to `1000ms`
13. Let's change the Screen Interaction now:
14. Select Splash Loading Interaction icon
	- Action: `Change Screen State...`
	- Screen: `Splash Loading`
	- State: `State 2`
	- Delay: `1000`
15. Select `Callback` to add a following interaction
	- Action: `Go to Screen`
	- Screen: `Splash Home`
	- Transition: `Fade`
	- Duration: `1000`
	- Easing: `Ease out`
	- Delay: `1000`
16. `Save` and `Preview`

### Step 04 - Battery Screen
1. Create `New Screen`
2. Double-click on the `01-battery-hi` asset
3. Add `Callback` to `Splash Loading` interaction to go to `Battery` screen at the end of the interaction.
	- Action: `Go to Screen`
	- Screen: `Battery`
	- Transition: `Slide Left`
	- Duration: `400`
	- Easing: `Ease in - Quart`
	- Delay: `0`
4. `Save Interaction`
5. Add `02-battery-lo` asset
6. From the Library, drag `Interaction Area` element onto canvas
7. Rename interaction area to `toggle-lo-hi`
	- Action: `Toggle item visibility (hide/show)` 
	- Screen: `Battery`
	- Item: `01-battery-hi.png`
	- Duration: `400`
	- Easing: `Ease out - Quad`
	- Delay: `0`
8. Save interaction, Save & Preview

### Step 05 - Create and Link Screens
1. Create `3 New Screens`:
	- Harness	
	- Appliances
	- Add
	- Scan
	- Select
	- Grid
2. Add design assets to each screen accordingly

### Final Step - Navigation Container
1. Create a container
2. Build only `State 1` with all possible buttons 
3. Add interaction to each navigation button
4. Add interaction to `Add` and `close` buttons
5. Fine tune animations