# Modoling
Modo workflow customization.

This is about how to make Modo modeling experience smoother.

These are my Modo config that helps me speed up my modeling process.

If you would like to know more about how to customize you Modo, my config set is a good point to start, in stead of head first to Modo's official documents. You can apply these files, guess how they work, then read some documents with your questions. It may be more efficient this way.

Also, you can check Warren Marshall's video tips about Modo config (https://www.youtube.com/watch?v=wv3DC_GggFw).

Some customizations requires Etereae's kits and Seneca's scripts, you can get them from links below
http://www.etereaestudios.com/docs_html/general_index_htm/resources.htm
http://dl.dropbox.com/u/1615250/senemodo.zip


some information about Seneca's scripts: http://www.indigosm.com/modoscripts.htm

### **About these config files:**
**_GooseBig's InputRemapping.CFG_**, this file contains all my key remapping. Most of them are context-sensitive tool specific shortcuts, like while you are using bevel tool the 'A' and 'D' become decrease and increase bevel levels. The others are customized pie menu hotkeys and some other popovers. If you want to change hotkeys of my pie menus, you need to edit this file.

**_3D gang Disable.CFG_**, disabled a bunch of 3D Gangs of primitives tools. I never used them once, and they take a lot of the UI space if you don't have a big enough monitor you will have to click the ">>" icon to find the 'Apply' button to make you primitive. I also moved the 'Apply' button to the top.

**_Action Center Pie.CFG_**, modified Modo's 'Action Center' pie menu. Added 'Axis' pie menu as a sub at 6 o'clock direction. And you can easily adjust it in the 'Form Editor'. So you don't need to select Action Center from the menu above. A lot of hotkeys will be freed from you left-hand side keyboard; Action Center shortcuts took a lot of useful keys, you can use them elsewhere now. Hotkey is 'Alt + A'.

**_Background Mesh Display Pie_Fixed.CFG_**, fixed the 'Same as Active' option can turn those mesh items back to 'Inactive'.

**_Falloff Pie.CFG, Viewports.CFG_**, a pie menu include all falloff type except 'Image Falloff'. Bind to 'Shift + F'.

**_ETEREA Primitives Enhanced.CFG_**, 'ETEREA Primitives' kit required. Actually, you need to use this file to replace the 'eterea_primitives.CFG' file or use the code in this config to replace the code in 'eterea_primitives.CFG' file. This config makes you can active primitives tools by using 'ETEREA Primitives'.

**_GooseBig's 3D Context Modeling Operation Menu.CFG_**, basically the same thing as 'Modeling Operations' menu while you right click on a 3D element. This only makes it quicker and cleaner. I bind this on the 'Space bar'.

**_GooseBig's Duplicate and Instance Pies.CFG_**, two pie menus for duplicate and instance clone. 'Alt + D' is the duplicate pie, instance pie binds to 'Ctrl + Alt +D'.

**_GooseBig's Macros.CFG_**, macros I made for these pie menus.

**_GooseBig's Modeling Operation Pie.CFG_**, the most important pie menu for myself, helps me do thing quickly. eg. merge vertices without popping up dialog window need you to confirm. Options pretty self-explained, w/o means "without popups". Options with '...' means it opens a sub pie menu. Bind to 'Shift + Space'.

**_GooseBig's Selection Set Pies.CFG_**, quick create and edit a selection set and a sub pie menu for creating and editing a selection set called 'UV seam'. Bind to 'Alt + W'.

**_Sen's Random Selector.CFG_**, quick access Seneca's random selection scripts. 'Alt + S'.

**_Sen's Script and GUI toolbar icon.CFG_**, simply added a button on the 'modo modes toolbar' for 'Sen_Scripts and Guis' palette.

### **How to install**:
Modo menu bar "System/Open User Configs Folder" open the folder "C:\Users\USERNAME\AppData\Roaming\Luxology\Configs", and just put these files in(except 'ETEREA Primitives Enhanced.CFG').
