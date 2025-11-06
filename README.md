# rust-cfg

# Custom key bindings for Rust
# ------------------------------------------------------------
# NOTE:
# The default key configuration file (keys_default.cfg) was removed intentionally.
# Keeping both files may cause conflicts or duplicated bindings,
# since Rust automatically merges configuration sources on startup.
# Use this file (keys.cfg) as the single source of truth for custom keybinds.
# ------------------------------------------------------------

bind tab +reload                    # Reload weapon or tool
bind return chat.open               # Open chat window
bind space +jump                    # Jump
bind 1 forward;sprint               # Move forward and sprint
bind 3 +slot2                       # Equip item in slot 2
bind 4 +slot3                       # Equip item in slot 3
bind 5 +focusmap                    # Focus the map view
bind 7 +holsteritem                 # Holster the active item
bind a +left                        # Move left (strafe)
bind c +slot5                       # Equip item in slot 5
bind d +right                       # Move right (strafe)
bind e lighttoggle                  # Toggle flashlight or headlamp
bind f +focusmap;+slot4             # Open map and equip item in slot 4
bind h inventory.toggle             # Toggle inventory
bind i +gestures                    # Open gestures menu
bind j clan.toggleclan              # Toggle clan menu
bind k +directionaldrop             # Drop held item in facing direction
bind m +map                         # Open map
bind n inventory.examineheld;+focusmap  # Examine held item and focus map
bind p +pets                        # Open pet interaction menu
bind q +slot6                       # Equip item in slot 6
bind r inventory.togglecrafting;inventory.togglecrafting;+use  # Open crafting and interact
bind s +backward                    # Move backward
bind t consoletoggle                # Toggle developer console
bind v inventory.togglecrafting     # Toggle crafting menu
bind w +forward;+sprint             # Move forward and sprint (redundant but useful)
bind x swapseats                    # Swap vehicle seats
bind y +opentutorialhelp            # Open tutorial/help
bind z +slot1                       # Equip item in slot 1
bind delete kill                    # Commit suicide (respawn)
bind keypad1 +notec                 # Musical note C
bind keypad2 +noted                 # Musical note D
bind keypad3 +notee                 # Musical note E
bind keypad4 +notef                 # Musical note F
bind keypad5 +noteg                 # Musical note G
bind keypad6 +notea                 # Musical note A
bind keypad7 +noteb                 # Musical note B
bind keypadplus +notesharpmod       # Sharpen note modifier
bind keypadenter +noteoctaveupmod   # Octave-up modifier
bind pageup +zoomincrease           # Zoom in
bind pagedown +zoomdecrease         # Zoom out
bind f1 consoletoggle               # Toggle developer console (alternative)
bind leftshift +altlook             # Free look while holding Shift
bind leftcontrol +duck              # Crouch
bind mouse0 +attack                 # Primary attack
bind mouse1 +attack2                # Secondary attack
bind mouse2 +attack3                # Tertiary attack (e.g. melee bash)
bind mouse3 +ping                   # Ping location
bind mouse4 +hoverloot              # Loot items by hovering
bind [leftcontrol+1] swaptoseat 0   # Swap to vehicle seat 0
bind [leftcontrol+2] swaptoseat 1   # Swap to vehicle seat 1
bind [leftcontrol+3] swaptoseat 2   # Swap to vehicle seat 2
bind [leftcontrol+4] swaptoseat 3   # Swap to vehicle seat 3
bind [leftcontrol+5] swaptoseat 4   # Swap to vehicle seat 4
bind [leftcontrol+6] swaptoseat 5   # Swap to vehicle seat 5
bind [leftcontrol+7] swaptoseat 6   # Swap to vehicle seat 6
bind [leftcontrol+8] swaptoseat 7   # Swap to vehicle seat 7
bind [leftshift+mousewheelup] +wireslackup     # Adjust wire slack (increase)
bind [leftshift+mousewheeldown] +wireslackdown # Adjust wire slack (decrease)
