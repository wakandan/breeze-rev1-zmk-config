# ZMK config for Breeze

A [ZMK](https://zmk.dev/) configuration for the Afternoon Labs Breeze keyboard.

## Using the Keymap Editor

1. Fork this repository.
2. Navigate to the keymap editor website and click on the GitHub icon or source on the top left.
	- https://nickcoutsos.github.io/keymap-editor/
3. Login to your GitHub account, follow the instructions, and select your fork.
4. A layout of the keyboard should now be visible and configurations can be made.
5. Once configured click on the "Save" at the top and add a commit message. This will begin to run the GitHub Action.
6. Go to the actions page of your fork.
	- https://github.com/<GH_Username>/breeze-rev1-zmk-config/actions
7. Click on the workflow of the commit message that was added. The workflow should be completed with a green check mark.
8. Download the firmware under "Artifacts" and extract to your desired folder.
9. Connect the **left** split keyboard to your computer and double click the reset button to put the board into bootloader mode.
10. Drag and drop `afternoon_breeze_left-nice_nano_v2-zmk.uf2` from your folder into the `NICENANO` device. It is normal for an error to occur once the copy is complete.
11. Disconnect the left side and repeat steps 9 and 10 for the right side.
12. Connect your keyboard to a computer by simultaneously clicking both reset buttons to go into pairing mode. 
