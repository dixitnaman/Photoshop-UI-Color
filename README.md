# Photoshop-UI-Color
This Rep Contains the UI Color code + Steps to change the UI Color of Photoshop 2020 or Higher

------ STEP: 1 ------

Go to your Photoshop installation folder.
"C:\Program Files\Adobe\Adobe Photoshop 2021\Required" or, wherever your installation folder is.

------ STEP: 2 ------

Find the "UIColors.txt" file and create a backup of it.

------ STEP: 3 ------

Search "rgb color picker" in Google and select your favorite color.
Preferably, choose a darker shade to go with all themes and texts.
Copy the RGB color code [RRR, GGG, BBB]

------ STEP: 4 ------

Place it in a temporary text file and add the fourth opacity parameter:
[RRR, GGG, BBB, 1.0]

------ STEP: 5 ------

Then open "UIColors.txt" file, and look for the below attributes.

WidgetButtonStroke = Widget buttons outline
WidgetButtonFillPressed = Selected widget buttons
WidgetPillStrokeFocused = Widget buttons outline on hovering
WidgetScrollbarArrows = Small arrows in the corner of the scrollbars
WidgetScrollbarElevatorFill = All Scrollbar
RulerText = Numbers on the ruler
ScrollingListSelectedDefault = Selected layers

------ STEP: 6 ------

Replace the color values in the grid with the value you created in STEP: 4.
Make sure you are replacing color values for all four themes, or at least for the theme you are using.
From top to bottom row, the four rows represent the PS themes as - Light Gray, Medium Gray, Dark Gray, Very Dark Gray.

------ STEP: 7 ------

Save the file.
If it required admin access, and gives you any such prompt, provide permission and save it.

------ STEP: 8 ------

Restart Photoshop for the changes to take effect.

Enjoy!

