* Version 1.7.0 - Vapok's Port
    * Updated Original Code Base to work with Hildir's Update
* Version 1.6.1
    * Fix camera's controller up and down movement.
* Version 1.6
    * Rebuild for Hearth and Home update.
    * Change build camera's controller up and down movement to reuse same buttons as controller jump and crouch.
    * Add support for ImprovedHammer from BuildIt mod.
* Version 1.5.1
    * Reduce spam when changing the two build distances (now uses LogDebug).
    * When changing the two build distances, be a little more agressive: change if current value is less than setting.
* Version 1.5
    * Change build distances: "distance can build from avatar" and "distance can build from workbench"
    * Fix gamepad joystick.
* Version 1.4
    * Stop ignoring the "Hide equipped tool/weapon" hotkey; allow it to put the tool away (and disable build camera).
* Version 1.3
    * Build Mode is usable with Hoe and Cultivator.
    * Don't turn build camera when user has piece selection HUD visible.
* Version 1.2
    * Fix camera panning (i.e. movement) speed: mousewheel does not change panning speed. Panning speed is about the same as walking speed. Hold shift to speed up. Add configuration option to change speed.
    * Don't allow looking so far up or down that camera is now upside down.
    * Camera turn speed respects user's Invert Mouse and Mouse Sensitivity options.
    * When entering build mode, we reset the view direction of the build camera, so that it matches the player's current view direction.
    * Add configurable option Move_With_Respect_To_World: When true, camera panning input (e.g. pressing WASD) moves the camera with respect to the world coordinates, not current camera view direction.
    * Don't move camera when user is in the menu, chat, etc.
    * Change Camera_Range_Multiplier default to 1 to provide an experience as close to vanilla as possible.
    * When the config option Verbose_Logging is true, explain 3 reasons why build mode is not activated.
* Version 1.1
    * Fix: don't only show the sky.
* Version 1.0.0.0
    * Initial release.