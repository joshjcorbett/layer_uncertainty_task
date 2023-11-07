# Help
This experiment was created using the PsychoPy3 Experiment Builder (v2022.2.4), to be run on a Windows PC.

## Mac error workaround 
There is a known issue with PsychoPy which can stop this script from running on Mac. This issue can be circumnavigated by following the steps below:
1) Open the .psyexp file in the PsychoPy builder and [convert to a python (.py) file](https://psychopy.org/gettingStarted.html#builder-to-coder).
2) Open the .py file in the PsychoPy coder.
3) Change defaultKeyboard = keyboard.Keyboard(backend='iohub') to defaultKeyboard = keyboard.Keyboard() (approx. line 142)
4) Delete the lines of code starting with "# --- Setup input devices ---" (approx. line 129) and ending with "eyetracker = None" (approx. line 139)
