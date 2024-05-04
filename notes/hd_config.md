# Hardware Configuration

# Topics
- [LogiOptions+ Alternative](#LogiOptions+-Alternative)

- - -

# LogiOptions+ Alternative
In this section we will explore an alternative to the official 
LogiOption+ application: `Solaar`.

## Install Solaar (Debian Subsystem: Ubuntu, LinuxMint, etc.)
```Bash
sudo apt install solaar
```

## Basic Configuration
Once the program is launched, it will be able to find your Mouse either by 
using the Bolt receiver or by connecting it via Bluetooth.

Below is an overview of what the program can manage by default:

![Basic Config](..%2Fasset%2Fimgs%2Fsolaar_basic_config.png)


## Advanced Configuration
To make the most of the mouse's capabilities, such as remapping the various side 
buttons available, `Solaar` provides the `Rule Editor`.

For example below, in addition to the default rules (under Built-in rules),
two new custom rules have been created:
- First rule: Opening the Terminal. Pressing the Smart Shift button (the central button 
  above the wheel) a Terminal will appear.
- Second rule: Show Working Windows. Pressing the Mouse Gesture Button (the button under 
  your thumb) the Windows left button will trigger.

![solaar_advanc_config.png](..%2Fasset%2Fimgs%2Fsolaar_adv_config.png)

**ATTENTION**: 
An important take to do to make these custom rules working, is to set the 
`Diversion` property in the default window. Otherwise, the changes will 
not be taken into consideration.
![solaar_smart_shift.png](..%2Fasset%2Fimgs%2Fsolaar_smart_shift.png)
![solaar_gesture_button.png](..%2Fasset%2Fimgs%2Fsolaar_gesture_button.png)
- - -
