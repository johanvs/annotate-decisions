# annotate-decisions
This webpage allows you to manually identify key data on a text. The selected area are stored in a json format that can be stored in a database.

In the source code the included text is a legal decision, and the user can tell who are the lawyer, the law and the party of this decision.

## Technology ##

Done in JavaScript with the framework [Vue.js](https://vuejs.org/)

# How to use it #

## Change the text ##

The text is hardcoded in script.js.

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

This project was created during 2016 Winter Session of [LION](http://joinlion.co/) from [The Family](https://www.thefamily.co/) to help the startup [Doctrine](https://www.doctrine.fr/).
