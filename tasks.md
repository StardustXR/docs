### due today
```tasks
root does not include templates
not done
short mode
hide tags
tags include task
due today
```

---

### due tomorrow
```tasks
root does not include templates
not done
short mode
hide tags
tags include task
due tomorrow
```

---

### all tasks
```tasks
root does not include templates
not done
short mode
hide tags
tags include task
```

---
## simula demo
bootkernel:
Hey Nova, Just wanted to know some things: what are the donation/setting bounty options for me? Through GitHub Sponsors and what else? PS I've looked at Open Collective but Indian banks restrict their payment methods or something based on what their customer support said. Github Sponsors is supported in India but I don't know if my payment method supports it. If needed I can directly transfer the funds to your bank account. I've a couple of requirements: The important part is that I'd need a receipt. I need to know if I'm paying you directly or paying Stardust XR Organization/Project (this is required)? On the receipt it should say "Display Server Improvements". Let me know! If you can share how the receipts gonna look like that'd be great - I just want to make sure the information just doesn't say supported Stardust XR project rather paid for "Display Server Improvements", "2D Window Manager Improvements" or something. Call this a bounty or donation whatever but I'd be happy starting with $100 and another ($100) (all one-time) after finishing. If you want a written agreement or an email, I'm happy to send one over. For the following features:
1. First class xorg support.
 2. Fix the upside down issue and the orientation issue so that the windows can't be rotated, fix the jitteriness when grabbing windows by hand, add grab aura etc.
3. Add a soft pop-up keyboard for Browser or any 2d app interaction with hands. (Smaller than Stereokit's preferred).
  
On a side note, I'm not sure if I should I ask you this but saying it anyways, since you're also a contributor at Monado, would it be possible to add two "monado-ctl" flags/features that resets the slam tracker and another flag that records (Northstar/DepthAI) either left or right cameras? I honestly don't have much time to do this but I'm happy to donate an additional $50 for this. My total donation/bounty will be therefore: $250, i.e $100 donation/bounty as an advance and the rest $150 after implementation. Please let me know what you think and I'm not posting any of these in the Stardust channels for confidentiality reasons. (edited)
   
Oh and the timeline to achieve these points, I know you gave me an estimate earlier but still.

simula demo is for cool showcase of stardust:

tasks for that (hardness/time/help/unimportance for simula, 1/10):

before headset:
- [x] make sure everything has a nix flake (?/?/7/10)=17 ✅ 2024-04-14
	- [x] atmosphere ✅ 2024-04-13
	- [x] gravity ✅ 2024-04-13
	- [x] flatland ✅ 2024-04-13
	- [x] protostar ✅ 2024-04-13
	- [x] non-spatial-input ✅ 2024-04-13
	- [x] poltergeist ✅ 2024-04-14
	- [x] comet ✅ 2024-04-14
	- [x] magnetar ✅ 2024-04-14
- [ ] make sure everything has .desktop files
	- [ ] atmosphere
	- [ ] gravity
	- [ ] flatland
	- [ ] protostar
	- [ ] non-spatial-input
	- [ ] poltergeist
	- [ ] comet
	- [ ] magnetar
- [x] new input protocol (1/2/0/10)=13 ✅ 2024-04-22
	- [ ] update clients
		- [x] atmosphere ✅ 2024-04-25
		- [x] flatland ✅ 2024-04-22
		- [x] protostar ✅ 2024-04-22
		- [ ] non-spatial-input
		- [ ] poltergeist
		- [x] comet ✅ 2024-04-25what
		- [x] magnetar ✅ 2024-04-24
- [x] nixos packages for stardust setups (?/?/?/5)=5 ✅ 2024-04-22
	- [x] give them config file ✅ 2024-04-22
- [ ] ultraleap in nixpkgs

with headset:
- [x] upside down issue ✅ 2024-04-11
- [ ] reduce jitter on flatland panel grab (?/?/6/7)=13
- [ ] improve grab aura on flatland panels (?/?/?/5)=5
- [ ] software keyboard for flatland (or separate) (?/?/?/6)=6
- [ ] patch up poltergeist for showing off panel shells (5/7/2/6)=20
- [ ] 3D tilt controller for game (probably neverball) (6/5/3/4)=15
- [ ] bring comet back from the dead (3/3/1/10)=17
	- [ ] eraser (rubbing paper gesture)
	- [ ] size changing somehow
	- [ ] find 3d models for stuff
	- [ ] probably different instances of comet (maybe have a builder?)
- [ ] demo 2 2D linux apps
- [ ] show off working on stardust in stardust (?/?/?/10)=10
- [ ] fix memory leak in server (?/?/?/3)

gonna take a while:
- [ ] implement xwayland (ideally rootless) (9/9/8/0)=36
- [ ] spatial persistence (need monado to impl https://registry.khronos.org/OpenXR/specs/1.0/html/xrspec.html#XR_MSFT_spatial_anchor_persistence with SLAM) (10/10/10/1)=31

## cl demo
- [ ] actually get a headset working my god
	- [ ] lynx
	- [ ] index
- [x] comet ✅ 2024-05-22
	- [ ] (optional) eraser
- [ ] vrchat productivity
	- [ ] frutiger aero world
	- [ ] working headset
	- [ ] show off krita
- [ ] immersive stardust demo
	- [ ] virtual camera
		- [ ] plug into v4l2loopback or pipewire whatever is fastest to impl
		- [ ] (optional) sync camera position to resonite to layer 
	- [ ] show off different environments
		- [ ] shed for passthrough like experience
	- [ ] niri
		- [ ] giant trading wall