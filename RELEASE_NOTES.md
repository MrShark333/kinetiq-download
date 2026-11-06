# KINETIQ 1.1.0

**Download:** `KINETIQ_1.1.0_x64-setup.exe` below (Windows 10/11, 64-bit). Double-click it; if Windows says *"Windows protected your PC"*, click **More info → Run anyway** (the installer isn't code-signed). It installs over earlier versions and keeps your macros.

SHA-256: `6b43bbf6682fd7e8204b9f44ed321e96bfbd064bce9087e708275ca4638ce265`

## What's new in 1.1.0

**Feels like Windows**
- Snap Layouts when the pointer rests on maximize, the system menu on right-click or `Alt+Space`, rounded corners, and the open macro's name in the taskbar and `Alt+Tab`.
- Context menus everywhere with `Shift+F10` or the Menu key; `F2` renames, `Del` deletes, `Ctrl+N` and `Ctrl+F` work as you'd expect.
- Deleting macros, steps or schedules offers Undo instead of asking "Are you sure?".
- Quitting saves what you were editing first.
- Accessibility: screen-reader names and states for every control, Windows Contrast themes, and "reduce motion".

**Recording and playback**
- Hotkey modifiers no longer end up in recordings, and keys whose release Windows hid (lock screen, admin apps) are released.
- *Only while it's active* holds every step, also inside repeats, conditions and called macros; a pause never splits a click in two.
- *Run program* opens files, shortcuts, folders and URLs; Store apps such as Calculator are matched by their own name.
- *Follow window* works for macros built by hand and stops clearly when its window is minimized.
- The run clock keeps counting through long waits.

**Editor**
- Bulk edits on 20,000-step recordings take milliseconds; number fields understand `60,000` and units like `2 s`.
- *Remove condition* keeps the Then steps; Play never runs an older copy when a save failed.
- A failed run offers *Show step*, which opens the macro at the step that failed.

**Image search and schedules**
- Images are found at any pixel offset, and a small change of colour no longer counts as a match.
- Schedules never run on Save or hours late after sleep, and show their next run in your own time format.
