# The Weather Machine
<img alt="GitHub social preview weather machine" src="https://github.com/user-attachments/assets/81ee483f-b809-4627-a7d7-da0617141763" />

## Purpose
This movie intends to showcase the features of the Dialogue Maker's version 5.0.0. Why are the patch notes a game? Because why *not?*

## Features highlighted
### Themes
* A brand new, pre-installed [StandardTheme](https://github.com/DialogueMaker/StandardTheme). The old one looked pretty bad, so here's to a more modern one! 
* A new [SubtitlesTheme](https://github.com/DialogueMaker/SubtitlesTheme). You can see this theme at the bottom of the screen during cutscenes.
* A new [ShockedTheme](https://github.com/DialogueMaker/ShockedTheme). 
* Setting themes per dialogue message and per character. You can see it when certain characters are shocked or are thinking about something.
* Effects that play during the dialogue. You can see the pre-installed [PauseEffect](https://github.com/DialogueMaker/PauseEffect). when certain characters are thinking.
* ClickToContinue is now optional on themes.
* You can now trigger dialogue using the [interact()]() method on DialogueClients.
* You can now continue dialogue using the [setDialoguePage()]() method on DialogueClients. You no longer need user input to do anything!

### Plugin features
Plugin features aren't visible on the game, so feel free to edit the place to see what's up.

* Dialogue Maker no longer needs a DialogueContainer folder or an NPCDialogueSettings ModuleScript. It doesn't even create a tag on your model. Everything's now in a nice, cozy DialogueServer module.
* Dialogue Maker doesn't need a server script anymore. Everything's done on the client by default, but you can still interact with the server using remote connections.
* Dialogue Maker has a light and dark theme.
* Dialogue Maker themes now use Rojo and are now fully responsible for parsing messages and handling responses. Redirects are still handled internally by DialogueClient for convenience. With this change, you don't need to follow a specific tree structure for a functional conversation.
* Dialogue Maker now relies more on Studio's Explorer, giving you more control of the .
* Dialogue Maker can now be opened by selecting a BasePart, a Model, a DialogueServer ModuleScript, or a ModuleScript descendant under a DialogueServer ModuleScript. 
* Redirects now use ObjectValues. This helps especially if you move them across the tree using the Explorer.

## License
This work is licensed under the GPL-3.0 license. Feel free to use or improve it, but be sure to give credit.

## Plot
### Skating through the ice in chaotic weather

## Credits
### Created by
[Christian Toney](https://github.com/Christian_Toney)
