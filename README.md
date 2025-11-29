# Rust-Binds
My console/settings binds for the game

extra:
environmentfishmanager.maxfishdistance 0
environmentfishmanager.maxfishpertype 0 

console binds only:
// Crafts default items using common resources
bind 0 craft.add -97956382 1;craft.add 15388698 10;craft.add 1390353317 5

// Respawns while in the death-screen
bind k respawn

// Changes lookatradius, makes it easier to spot dropped items and upgrade walls behind TC
bind l ~meta.exec "client.lookatradius 0" "chat.add 0 0 MIN";meta.exec "client.lookatradius 0.2" "chat.add 0 0 DEFAULT";meta.exec "client.lookatradius 10" "chat.add 0 0 MAX"

// Turns off sounds for engine when staying in the radius (press it when you hear it)
bind p audio.speakers 2;showtoast 3 "Sounds: OFF" 1

//Toggle zoom
bind mouse2 ~graphics.fov 70;graphics.fov 90

// Disables scroll to change hotbar slot
bind mousewheelup no_input
bind mousewheeldown no_input

// kill bind
bind [leftshift+k] no_input // Accidental, can't clear it for some reason
bind [leftshift+delete] kill


full list:
bind tab inventory.toggle
bind return chat.open
bind space +jump
bind slash +markcurrentpos
bind 0 craft.add -97956382 1;craft.add 15388698 10;craft.add 1390353317 5
bind 1 +slot1
bind 2 +slot2
bind 3 +slot3
bind 4 +slot4
bind 5 +slot5
bind 6 +slot6
bind 7 +holsteritem
bind 8 no_input
bind 9 no_input
bind a +left
bind b +gestures
bind c +duck
bind d +right
bind e +nextskin;+use
bind f +focusmap;lighttoggle
bind g +hoverloot
bind h +hoverloot
bind j clan.toggleclan
bind k respawn
bind l ~meta.exec "client.lookatradius 0" "chat.add 0 0 MIN";meta.exec "client.lookatradius 0.2" "chat.add 0 0 DEFAULT";meta.exec "client.lookatradius 10" "chat.add 0 0 MAX"
bind n inventory.examineheld
bind p audio.speakers 2;showtoast 3 "Sounds: OFF" 1
bind q +prevskin;+slot4
bind r +reload
bind s +backward
bind t +firemode
bind v inventory.togglecrafting
bind w +forward
bind x swapseats
bind y swaptoseat 0
bind z +ping
bind pageup +zoomincrease
bind pagedown +zoomdecrease
bind f1 consoletoggle
bind capslock +map
bind rightshift +autowalk
bind leftshift +sprint
bind leftcontrol +altlook
bind mouse0 +attack
bind mouse1 +attack2
bind mouse2 ~graphics.fov 70;graphics.fov 90
bind mouse3 +slot6
bind mouse4 +slot5
bind mouse5 no_input
bind mousewheelup no_input
bind mousewheeldown no_input
bind [leftshift+k] no_input
bind [leftshift+delete] kill
