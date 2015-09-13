# ableton-pd-xbox360

Introduction

This is my attempt at creating an interface so that I can use an Xbox 360 control pad with Ableton Live. I created similar interfaces with Glove PIE before but as that program is no longer being developed and doesn't work with Windows 8, I thought I would see if I could create a new version using Pure Data (http://puredata.info/). Pure Data also has the benefits of being cross platform compatible, and therefore should allow people to use the same interface with Mac OSX and Linux based set ups.

Note: So far I have only tested this set up on a x64, Windows 8.1 based system running Ableton 9 suite. It *should* work fine on similar set ups I haven't been able to test it on any other machines yet so no guarantees.

I should say that this script was HEAVILY based on Leonard J. Paul's USB Controller script which you can find at http://www.ecuad.ca/~lpaul/FinalProjects2/. The main difference was that I wanted to split the 4 directions of each thumbstick in to individual cc controls and also add mappings for all of the standard Xbox 360 control pad buttons.

Required software:

- Pure Data extended: http://puredata.info/downloads/pd-extended
- Ableton Live: https://www.ableton.com/en/live/
- loopMIDI: http://www.tobias-erichsen.de/software/loopmidi.html (or similar virtual midi software)

Required hardware:

- Xbox 360 control pad (wired or wireless)
- Wireless Gaming Receiver For Windows (if you're using a wireless pad obviously)
- Computer running Windows 8.

FAQs
- Q: Why use an Xbox 360 control pad with Ableton?
	- A: The 2 analogue thumbsticks and multiple buttons and triggers allow for a lot of controling options which therefore works well with Ableton Live's mapability. So why not?	
	
Version information:

1.0
- Joypad dead zone FINALLY implemented!!!
- As well as standard version (NoModes), there is a new version (Modes) which adds the ability to use the left and right bumper buttons to activate / deactivate controls on 2 different FX racks.
- Updated standard example ableton set ("Modes")
- New example set for "No Modes" set up

0.1
- First public release
	- Pure Data scripts for the interface and creating the mappings in Ableton Live
	- Sample Ableton Live project (created in Ableton Live 9 Suite)
	- README file created 
