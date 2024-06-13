Avrae-Bastions

This repo is designed to store the code for the Bastions plugin for Avrae. Since there is no integration between Avrae Workshop and GitHub, the code here may be a higher version than what is published on the Workshop. If you see this is out of date and you'd like it updated, please create an Issue and I will try to get that resolved - I might have forgotten!

Bastions are an optional rule created by Wizards of the Coast in their Unearthed Arcana. They allow players to have small places to call home between sessions called "Bastions" which can impart benefits and have an action system of their own. Further details on bastions can be found in the Bastions.md file in this repository - this is a markdown version of the Unearthed Arcana rules. 

I plan on adding a few suggested homebrew modifications to the system. When adding the alias to a server, the server owner will have the option to update default values to use these homebrew changes instead. Some are as simple as text changes (preserved as the default but suggested for clarity), while others may have mechanical changes such as expanding the requirements for the "Training Ground" Special Facility.

My goal is for the following TENTATIVE commands to exist. Some may be different or omitted, and some may be added.

- !bastion
    This command should display current bastion info. It won't display descriptions but will provide facility types and sizes, which should be most of what a plain details sheet should need. It may also include defenders and stuff.

- !bastion create
    The command that starts it all for people, this should allow players to create a bastion at level 5. 

- !bastion facilities
    This will give some basic info on how to call the sub-commands and not do anything itself. Probably.

- !bastion facilities basic
    This should list all basic facilities

- !bastion facilities special
    This should list special facilities, likely in a compressed or paginated format. Perhaps requiring an argument.

---

I want to make bastions very server-configurable. Does your group want bastions to start at level 1? Great! Want to up the amount of special facilities you get at different levels? Sure! Add custom facilities? You got it!