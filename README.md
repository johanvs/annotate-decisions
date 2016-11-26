# annotate-decisions
A front interface to quickly annotate parts of a text by selecting them.

In a given text you want to find key data, but you cannot automatise this findind : it needs to be done by a human. This interface allows the user to tell the system what are the key data of the text. It is done with an interface where you select parts of the text, and tell what they correspond to.

Here the text is a legal decision, and the user has to find who are the lawyer, the law and the party of this decision.

# How to use it #

## Change the text ##

The text is harcoded in script.js.

## Add annotations ##

Select a part of the text with your mouse, and click on a colored button corresponding to your selection.

## Remove an annotation ##

Click on an annotation to remove it (when you hover an annotation the cursor is a trash)

You can clear all the annotations with the clear button

## Export the annotations ##

Click on Export, and a json is generated below containing the annotations. You can store this json in your backend.

## Import the annotations ##

Paste your json in the textarea, and click on Import. The current annotations are then replaced with the new ones.  


# Notes #

This project was created in [LION](http://joinlion.co/), a training of [The Family](https://www.thefamily.co/) to help [Doctrine](https://www.doctrine.fr/).