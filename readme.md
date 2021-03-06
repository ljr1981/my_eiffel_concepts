
https://user-images.githubusercontent.com/1668502/110876570-c1f1dc00-82a5-11eb-8bbe-a5fb8f0aeed0.mp4

# My Eiffel Concepts
A demonstration of Eiffel concepts

## Pick-n-Drop
Drag-n-drop is okay until it's not--that is--your finger stops depressing the mouse-button for any reason and you drop the item being dragged in the wrong place!

Pick-n-drop is not drag-n-drop.

### Turn on Pick-n-Drop
In Eiffel Studio, click Tools --> Preferences.

![Preferences](/docs/tools_prefs.png)

Click the "Search ..." button and then type "pick" in the Filter.

Find the "General.Pick and drop (pnd).mode" and ensure the Literal Value is set to "True" (checked on)

[Setting Pick-n-Drop Prefs example video](https://player.vimeo.com/video/522518751)

### Using Pick-n-Drop
it's all about things that are "Pickable" and their "Legal Drop-targets"—that is—where you can legally "drop" the pebble that appears when you start the PnD.

#### Starting Pick-n-Drop
Right click something like a class name. When you do, you will get a "pebble" tied to what you picked with a flexing rubberband dotted line.

To cancel the Pick-n-Drop, just press the ESC key or drop anywhere other than a drop-target.

To complete the Pick-n-Drop, drop the pebble onto a legal drop target. For example, the class can be dropped on the Class Context Tool.

[Pick-n-drop example video ](https://player.vimeo.com/video/522514198)

## Code Analysis Tool
Click the Analyze toolbar button and perform analysis. Double-click issue to be taken to them in code. Fix them and re-run the Analyzer to see if issues remain.

[Quick CA demo video](https://player.vimeo.com/video/522525817)


# IDE Core Tools
The Eiffel Studio IDE consists of a number of core parts. These can be roughly summed up in a bullet-list of the most interesting of each.

* Menus
	* Project
	* Execution
	* Tools
* Toolbars
	* Project Settings
	* Compile
	* Analyze
	* Run
* Editor
	* One tab per class
	* Tabs docking
* Views
	* Groups View (of project)
	* Features View (current Editor tab)
	* AutoTest Tool
	* Favorites List
* Context Tools
	* Class
	* Feature
	* Outputs
	* Error List
	* AutoTest Results

## Core Workflow
Understanding the Eiffel Studio IDE means understanding common workflows. Typical workflows will involve the GUI items from the list above. The items below presume a project to already be open in the IDE.

* New Class [Create New Class Video](https://player.vimeo.com/video/522952985)
* Compiling [Compile Overview Video](https://player.vimeo.com/video/523303904)
* Opening & Compiling [Open & Compile Overview Video](https://player.vimeo.com/video/523448308)

## Class Context Tools

[Context Tools Overview Video](https://player.vimeo.com/video/523299768)

The Class Context Tool allows you to explore various aspects of your Eiffel classes. For example, the first four buttons of the Class tool are:

* Clickable View
* Flat View
* Contract View
* Interface View

[Class Context Views Video](https://player.vimeo.com/video/522785011)

* Ancestors
* Descendants
* Clients
* Suppliers

[Class Context Inheritance Video](https://player.vimeo.com/video/522793269)

* Attributes (properties)
* Routines (methods)

[Class Context Attribute and Routine Video](https://player.vimeo.com/video/522798002)

* Invariants

[Class Context Invariants Video](https://player.vimeo.com/video/522812608)

* Creators (Constructor methods)

[Class Context Creators Video](https://player.vimeo.com/video/522815495)

* Deferred features (attributes/routines without implementation code)

[Class Context Deferred Video](https://player.vimeo.com/video/522819542)

* Once features (constants or routine singletons)

[Class Context Once function Video](https://player.vimeo.com/video/522824157)

* Instance-free Features

[Class Context Instance-free Video](https://player.vimeo.com/video/522896219)

* External features (in-line C/C++, external .h/.c/.cpp, libs, objs etc)

[Class Context Externals Video](https://player.vimeo.com/video/522902554)

* Exported features (like public, private, protected, hidden)

[Class Context Exported Video](https://player.vimeo.com/video/523142196)

## Feature Context Tool

[Feature Context Overview Video](https://player.vimeo.com/video/523162219)

The Feature Context Tool allows you to explore various aspects of the features of your Eiffel classes. For example, the first two buttons of the Feature tool are:

* Basic Text View
* Flat View

[Feature Context Basic & Flat Video](https://player.vimeo.com/video/523154438)

* Callers

[Feature Context Callers Video](https://player.vimeo.com/video/523156758)

* Inheritance Views
	* Implementors -- who provides code in what class?
	* Ancestors (parents) -- what parents have what version?
	* Descendants (children) -- what children inherit this feature in what class?
	* Homonym's -- what classes have the same feature name but non-related?

[Feature Context Inheritance Video](https://player.vimeo.com/video/523230801)


