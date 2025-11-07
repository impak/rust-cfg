# rust-cfg
## Custom key bindings for Rust

NOTE: The default key configuration file (keys_default.cfg) was removed intentionally.
Keeping both files may cause conflicts or duplicated bindings,
since Rust automatically merges configuration sources on startup.
Use this file (keys.cfg) as the single source of truth for custom keybinds.

#### Reload weapon or tool
```
bind tab +reload                    
```
#### Open chat window
```
bind return chat.open               
```
#### Jump
```
bind space +jump                    
```
#### Move forward and sprint
```
bind 1 forward;sprint              
```
#### Equip item in slot 2
```
bind 3 +slot2                      
```
#### Equip item in slot 3
```
bind 4 +slot3                       
```
#### Focus the map view
```
bind 5 +focusmap                    
```
#### Holster the active item
```
bind 7 +holsteritem                 
```
#### Move left (strafe)
```
bind a +left                        
```
#### Equip item in slot 5
```
bind c +slot5                       
```
#### Move right (strafe)
```
bind d +right                      
```
#### Toggle flashlight or headlamp
```
bind e lighttoggle                  
```
#### Open map and equip item in slot 4
```
bind f +focusmap;+slot4             
```
#### Toggle inventory
```
bind h inventory.toggle             
```
#### Open gestures menu
```
bind i +gestures                    
```
#### Toggle clan menu
```
bind 0 clan.toggleclan              
```
#### Drop held item in facing direction
```
bind k +directionaldrop             
```
#### Open map
```
bind m +map                         
```
#### Examine held item and focus map
```
bind n inventory.examineheld;+focusmap  
```
#### Open pet interaction menu
```
bind p +pets                        
```
#### Equip item in slot 6
```
bind q +slot6                       
```
#### Open crafting and interact
```
bind r inventory.togglecrafting;inventory.togglecrafting;+use  
```
#### Move backward
```
bind s +backward                    
```
#### Toggle developer console
```
bind t consoletoggle                
```
#### Toggle crafting menu
```
bind j inventory.togglecrafting     
```
#### Move forward and sprint (redundant but useful)
```
bind w +forward;+sprint             
```
#### Swap vehicle seats
```
bind x swapseats                    
```
#### Open tutorial/help
```
bind y +opentutorialhelp            
```
#### Equip item in slot 1
```
bind z +slot1                      
```
#### Commit suicide (respawn)
```
bind delete kill                    
```
#### Musical
```
bind keypad1 +notec                 
```
```
bind keypad2 +noted                
```
```
bind keypad3 +notee                 
```
```
bind keypad4 +notef                 
```
```
bind keypad5 +noteg                 
```
```
bind keypad6 +notea                 
```
```
bind keypad7 +noteb                 
```
#### Sharpen note modifier
```
bind keypadplus +notesharpmod       
```
#### Octave-up modifier
```
bind keypadenter +noteoctaveupmod  
```
#### Zoom in
```
bind pageup +zoomincrease           
```
#### Zoom out
```
bind pagedown +zoomdecrease         
```
#### Toggle developer console (alternative)
```
bind f1 consoletoggle               
```
#### Free look while holding Shift
```
bind leftshift +altlook             
```
#### Crouch
```
bind leftcontrol +duck             
```
#### Primary attack
```
bind mouse0 +attack                 
```
#### Secondary attack
```
bind mouse1 +attack2                
```
#### Tertiary attack (e.g. melee bash)
```
bind mouse2 +attack3                
```
#### Ping location
```
bind mouse3 +ping                   
```
#### Loot items by hovering
```
bind mouse4 +hoverloot             
```
#### Swap to vehicle
```
bind [leftcontrol+1] swaptoseat 0  
```
```
bind [leftcontrol+2] swaptoseat 1   
```
```
bind [leftcontrol+3] swaptoseat 2  
```
```
bind [leftcontrol+4] swaptoseat 3   
```
```
bind [leftcontrol+5] swaptoseat 4   
```
```
bind [leftcontrol+6] swaptoseat 5   
```
```
bind [leftcontrol+7] swaptoseat 6   
```
```
bind [leftcontrol+8] swaptoseat 7  
```
#### Adjust wire slack (increase)
```
bind [leftshift+mousewheelup] +wireslackup    
```
#### Adjust wire slack (decrease)
```
bind [leftshift+mousewheeldown] +wireslackdown 
```


