A work in progress auto-completion Schema json file for Stormgate Triggers.

Made in order to increase QoL and simplify entry into the script editing to make triggers, by adding auto-suggest lines for the function_ids and some other elements used in triggers.

Requires ([Visual Studio Code (User)](https://code.visualstudio.com/download))

The editor custom maps on your PC are located in the Documents/Stormgate. We're going to turn it into a VSCode workspace that can read Schemas placed in it.
You can download the Schema file(s) and place them there (<>Code -> Download ZIP).

Open the Stormgate folder in VSC.

<img width="1637" height="876" alt="json schemas guide 3" src="https://github.com/user-attachments/assets/2f4cfe51-010f-415b-b720-51312a175057" />

This creates the workspace file. Opened this way and read as workspace, the folder can be set up in a way that allows the Schema to work. This creates .vscode folder and the workspace file there.

<img width="1829" height="1011" alt="json schemas guide" src="https://github.com/user-attachments/assets/bdb8008a-3a21-4413-ac3c-c758cb05143f" />

Now we need to find the setting that sets the Schema in the Workspace. After going to Preferences -> Settings , search "json.schemas" and you'll get the entry.

<img width="711" height="428" alt="json schemas guide 2" src="https://github.com/user-attachments/assets/69043dca-cab1-44aa-a925-d83fde692b0a" />

You'll get the settings.json file, located in the .vscode folder. Edit the file like this (because it's in the core of the workspace, Schema doesn't need a larger path. Also using web urls or local file urls without a workspace simply didn't work for me.)

And... we're done! The only thing you need to remember is to open a scheme in a tab beforehand (I don't know why that's required, but it seems to be).

https://github.com/user-attachments/assets/53471f86-de55-49a4-8f7b-6c2ff4fbce08


