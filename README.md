# RoboLamp

## Preset Buttons

Each preset button has three actions:

| Button | Single click | Double-click | Long press |
| --- | --- | --- | --- |
| 1 | Recall preset 1 | Select Distracted mood | Save the current lamp state to preset 1 |
| 2 | Recall preset 2 | Select Happy / excited mood | Save the current lamp state to preset 2 |
| 3 | Recall preset 3 | Select Moody mood | Save the current lamp state to preset 3 |
| 4 | Recall preset 4 | Select Focused mood | Save the current lamp state to preset 4 |

Presets store the lamp's head position, height, and lighting settings, including
light mode, color, and brightness. A single click is recognized after a brief
wait so the firmware can distinguish it from a double-click.

## Directional Controller

- Move the joystick left/right and up/down to steer the lamp head. Small inputs
	are ignored, and the servo response is smoothed.
- Press the joystick button to enter color selection. Move left/right to choose
	a color or white temperature, and up/down to change brightness. Press the
	joystick button again to apply the selection and exit.
- Hold the separate Up or Down button to raise or lower the lamp. Release to
	stop. These buttons do not move the lamp while color selection is active.
- In Distracted or Moody mode, a very brief joystick nudge can trigger a return
	toward the saved head position.