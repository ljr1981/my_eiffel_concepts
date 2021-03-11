# My Eiffel Concepts
A demonstration of Eiffel concepts

## Pick-n-Drop
Drag-n-drop is okay until it's not--that is--your finger stops depressing the mouse-button for any reason and you drop the item being dragged in the wrong place!

Pick-n-drop is not drag-n-drop.

### Turn on Pick-n-Drop
In Eiffel Studio, click Tools --> Preferences.

![Preferences](/docs/tools_prefs.png)

Click the "Search ..." button and then type "pick" in the Filter.

Find the "General.Pick and drop (pnd).mode" and ensure the Literal Value is set to "True" (checked on).

### Using Pick-n-Drop
it's all about things that are "Pickable" and their "Legal Drop-targets"—that is—where you can legally "drop" the pebble that appears when you start the PnD.

#### Starting Pick-n-Drop
Right click something like a class name. When you do, you will get a "pebble" tied to what you picked with a flexing rubberband dotted line.

To cancel the Pick-n-Drop, just press the ESC key or drop anywhere other than a drop-target.

To complete the Pick-n-Drop, drop the pebble onto a legal drop target. For example, the class can be dropped on the Class Context Tool.

<iframe title="vimeo-player" src="https://player.vimeo.com/video/522514198" width="640" height="438" frameborder="0" allowfullscreen></iframe>