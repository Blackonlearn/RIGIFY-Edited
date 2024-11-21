<!-- FEATURES -->

## Custom Rigify
This project enhances Blender's Rigify add-on by introducing the ability to set a custom basename for your rig. The basename dynamically updates key elements of the rig and generates a UI panel category that corresponds to the basename.


## Features

![Feature 001](https://github.com/user-attachments/assets/0b05113b-18d4-49cd-a74f-15ceeb124aa1)

1. **Custom Basename Support:**
      - [ ] Define a custom basename using the rigify_rig_basename property in the Armature's data.
      - [ ] Automatically rename:
          - The RIG object and its associated RIG data.
          - The META object and its associated META data.
2. **Dynamic UI Panel Category:**
      - [ ] The Rigify UI panel appears in the N-panel under a category matching the rig's basename.
      - [ ] If no basename is set, it defaults to "Rigify".

## Installation

### **Step 1: Clone or Download:**
   ```sh
   git clone https://github.com/Blackonlearn/RIGIFY-Edited
   ```
### **Step 2: Locate Blender's Add-ons Directory:**
   - Windows
   ```sh
   C:\Program Files\Blender Foundation\Blender 3.6\3.6\scripts\addons\rigify
   ```
   - Linux
   ```sh
   /usr/share/blender/3.6/scripts/addons/rigify
   ```
   - macOS
   ```sh
   /Applications/Blender.app/Contents/Resources/3.6/scripts/addons/rigify
   ```
### **Step 3: Replace the Files:**
   Copy and replace the modified files into the rigify folder:
   - ui.py
   - generate.py
   - rig_ui_template.py
   - utils/rig.py
   
### **Step 4: Restart Blender**
   Restart Blender to ensure the updated Rigify add-on is loaded.

### **Step 5: Enable Rigify**
    1. Open ``` Edit > Preferences > Add Ons.```
    2. Search for _Rigify_ and ensure it is enabled
