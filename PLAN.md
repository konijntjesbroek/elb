## Electronical Lab Book
_created by:_ Arlo Gittings
_created on:_ TBD

### Description:

A small, modular device that can be broken down into minimal components for
storing and travel. The device will be based on a a single board computer and
utilize ssd(s) for storage. While I was originally leaning toward using a 
raspberry pi for the design, there are a few issues that are making this less
appealing.

- Arm based technology. One of the tools I use on the regular for creativity
  is Aesprite (pixel drawing tool). While this is a community supported tool
  and I strongly believe in their ethos, it is only available on x86 platforms
  for now.
- Storage limitations. The stock raspberry pi is decently capable for most 
  applications, but if you want to use large storage, you have a couple of
  choices.
	- A monolithic sd install which is susceptible to corruption because of
	  power fluctuations, which become more prevalent when you add in a second
	  storage device by usb.
	- Split install on usb drive. This can be used as boot drive after the 
	  initial install. There is less issue with the corruption because of
	  safeguards on the external ssd, but the power issue is still there and
	  will lead to brownout conditions.
	- A secondary motherboard that hosts the rpi as a compute module and makes
	  storage and memory expandable. This is nice, but ups the costs,
	  significantly.
- Power constraints. The rpi runs on 5v ~2A, this is great for small and light
  projects, but it cannot source much external current or anything over 5 
  volts. Coming from the radio world a wider operating range and amperage 
  source would be useful. 
- Graphics. Although the primary function of this device is not graphics heavy,
  part of the intended use is for archiving films and even minimal transcoding
  on the device leads to significant downtime. Any sort of editing or encoding
  of video is not realistic.

### Device Layout    
- Useful collection of media for when I am off grid
	- Electronics
    - Machining
    - Carpentry
	- Architecture
	- Math
	- Science
	- History / Folklore
	- Craft and Lifestyle
	- Entertainment and Culture
	- Repair manuals for common goods
		- Radio
		- Bicycle
		- Small Engines
		- Cars/Trucks
		- Plumbing
		- Generators
		- HVAC/Refrigeration
		- Appliances
- Streamlined data entry
	- simple method to collect ideas
	- method to review and organize notes and ideas
	- long term method for storage of active projects
	- off device storage of backups
- Tools
	- Creation, editing, viewing of media
		- nvim
			- vim-plug
			- lexical
		- LaTEX
		- calibre ?
		- Aseprite
		- spice
		- audacity/ardour
		- mp3 tools ?
		- vlc
		- handbrake?
		- OCR
	- Integrated observation
		- Telescope
		- Document Scanner
		- O-scope
		- Multi-meter
		- LC meter
		- Radio analyzer
		- GPS
		- Weather
		- Network testing 
		- Pen Testing
	- Communications
		- Radio
		- Text based
		- WiFi
		- Ethernet
	- Language tools
		- Dictionaries
		- Translation tools
	- Programming
	- IC and Logic cross reference.
- Modular
	- Singular Power/Port rail
	- externals:
		- power (optional 5 or 12v)
		- storage
		- processor
		- video
		- e-ink display
		- controlable I/O
		- input devices (kbd/pointer, plus tools above).
		- Network
- Rugged
	- Dust, water, shockproof
	- No moving drives

### Success Factors

