Keymapper v1.1
==

A fork from pate's Keymapper, to map the Caps Lock key to a Control key.
	
How it Works
--

Caps Lock keypresses are intercepted with a global keyboard hook (SetWindowsHookEx). A control keypress is then simulated in its place to improve touch typing using the keybd_event function.

Known Issues
--

Certain anti-virus heuristics may classify the executable as a potential threat due to the keylogging potential of a global keyboard hook. A more permanent way to remap your keyboard is using a registry tool like SharpKeys.