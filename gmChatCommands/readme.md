# Purpose
The gmUtilities file is a collection of abilities that are entered into an empty character sheet. This provides a convenient and clean way to call abilities which are actually API macros from the chat. The configuration is set to whisper to the GM so it won't pollute the player's chat.

# Requirements and Acknowledgements
This feature requires the use of API scripts and as such it requires a Roll20 Pro subscription. The following API scripts are required in order to run all of these. 
EncounterHelper, created by Kurt Jaegers.
GroupCheck, created by Jakob.
TokenMod, created by The Aaron.
TokenNameNumber, created by The Aaron
Token Action Maker, created by keithcurtis, based on original code by kevin, with assitance and additions by Oosh, GiGs, and bretmckee
Thank you all for your amazing contributions!

# Setup
There is a bit of setup involved with this utility but isn't overly complicated, please follow the step-by-step guide below.
1. Create a blank character sheet, you can name it gmUtil (or whatever you like)
2. Edit the sheet directly
3. Go to Attributes & Abilities
4. Add an Ability named gmUtilities and check the "Show in Macro Bar" box
5. Copy the code from the utility file and past it into the second box
6. Hover over the newly built ability and click on the Check Mark to save the ability
7. **Optional Recommendation** beside the Check Mark is a d20 icon, click on that to test the ability it should output the ability into the game chat
8. Repeat the same steps for all the abilities using the relevant API macros as you see fit

# Troubleshooting
If you receive the following error, save your work and close your game. Reopen and it should work as expected. This seems to occur when editing abilites that are called by another ability which breaks the calls.
TypeError: Cannot read properties of undefined (reading 'substring')