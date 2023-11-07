This experiment was created using PsychoPy3 Experiment Builder (v2022.2.4), to be run on a Windows PC.

There is a known issue with running this task on Mac to do with 'ioHub'. This issue can be circumnavigated by editing the PsychoPy script directly, and running the task from the coder.

The edits that should be made:
1) Change defaultKeyboard = keyboard.Keyboard(backend='iohub') to defaultKeyboard = keyboard.Keyboard()
2) Delete the lines of code starting with "# --- Setup input devices ---" (approx. line 129) and ending with "eyetracker = None" (approx. line 139)