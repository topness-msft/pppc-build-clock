# CAPE @ PPPC 2026 build clock

Projector screen for the Feel the Power! build-a-thon. It counts down to the 6:30 PM welcome, puts **Build Time** front and center during the build (with the showcase countdown in the top-right card), brings the showcase countdown back to the middle for the table-winner pick, and shows the CrowdHum vote (QR code and hum.vote/POWR) for People's Choice.

Everything is in `index.html` (fonts embedded), so it also works offline: open the file in a browser and go full screen.

## On the night

- Move the mouse to show **Full screen** and **Operator**.
- **Operator** lets you shift upcoming items earlier or later, set the showcase time, start the next item early, undo, or reset to the printed agenda. Changes are saved in that browser for the day.
- **Preview a time** shows what the room will see at any moment. Press **Back to live** and **Reset to printed agenda** after rehearsing.

Times follow Las Vegas (Pacific) time regardless of the computer's time zone.

## Closing block (People's Choice, then judges' awards)

From the People's Choice time, the screen shows the CrowdHum vote. Move to the judges' awards with:

- **Next** beside the Operator button (visible when you move the mouse), or
- the **→ / Page Down** key, which is what most presentation clickers send (← / Page Up goes back), or
- the **Closing** picklist in the Operator panel.

### Adding the judges

Edit the `JUDGES` list near the top of the script in `index.html` (name and title for each), and add square photos as `judges/judge-1.jpg` … `judges/judge-4.jpg`. Until a photo is there, the judge's initials show in the circle.
