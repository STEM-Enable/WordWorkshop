# Using Windows Narrator (screenreader) for basic tests

## But do screenreaders read Word equations directly?

At the moment accessible equations in Word are relatively new - Microsoft have done/is doing the necessary work but some of the screenreader vendors/publishers have not yet implemented the interface. For screenreader users in this situation one of the following should be accessible:

* Word with equations converted using MathType (MathPlayer needs to be installed too)
* HTML Flex output from CAR

## Warning!

Learning to use a screenreader properly is well outside the scope of this workshop but having a basic understanding of how a screenreader can interact with a document is helpful. We will use a restricted mode of the built-in Windows screenreader Narrator which can read Word equations. Please also note that students will **certainly** have a screenreader more suited to education and employment than Narrator and that no student should be asked to change or acquire a skillset in a new screenreader without very good reason and plenty of advance notice. 

Please also note that these are instructions are not intended to teach you how to use a screenreader and they are not suitable for someone who usually uses a screenreader. These instructions exist solely to aid lecturers or teaching fellows in understanding how the structure of a Word document is used by a screenreader.

## What to do to have a go

1. Open the Word document you want to explore and click your cursor at the start.
2. Press **Windows key + Ctrl + Enter** to start Narrator.
   * To stop Narrator from finishing the current output press **Ctrl**
   * To stop Narrator completely press **Windows key + Ctrl + Enter**
3. Narrator has a mode which is mainly for scanning through and reading. We are only going to use this mode as it is easy for an untrained user to use with a Word document. You cannot edit the document when in this mode. 
   * To get in or out of scan mode press **CapsLock + Spacebar**
   * More information at <https://support.microsoft.com/en-us/help/22809/windows-10-narrator-using-scan-mode> 
4. Try not to use the mouse! Once in scan mode use the below commands to explore the document. Try to move through the document in different ways to 'scan' it. Try to read the equations.

| Key press   	  | What will happen?	       	       	     	      	| What can I add?				|
| --------------- |-----------------------------------------------------|-----------------------------------------------|
| Enter		  | Do action (in context)				| Add shift for a secondary action		|
| Down/Up	  | Read next/last item		   			| Add control for lines				|	
| Right/Left	  | Read next/last character	   			| Add control for words				|
| Home/End	  | Move to and read first/last character of line	| Add control for first/last line of text	|
| P		  | Read next paragraph			     		| Add shift for previous paragraph   		|
| H		  | Jump to next heading				| Add shift for previous heading		|
| n in {1,..,9}	  | Jump to next heading at level n			| Add shift for previous heading at level n	| 
| I    		  | Jump to next item	    	  			| Add shift for previous item	    	  	|
| K		  | Jump to next link					| Add shift for previous link			|
| T		  | Jump to next table					| Add shift for previous table			|

## Discuss

* What additional issues have you found with the document?
* Do you know what is causing them?

[Return to plan](index.html)
