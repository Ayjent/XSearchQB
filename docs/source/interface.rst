Interface
=========

The User Interface for the Query Builder is intended to change its display dynamically based on user input and selections.  The interface is intended to be intuitive and instructive as to how you must build search queries in the New X-Search application.

Literal Element Input
---------------------

This section of the Query Builder is where you will input Natural Language or any other set of characters you would like to create a pattern matching search query for.  When this input is modified it dynamically updates all output and interface options.

.. note::

  If you have modified your search query be careful to remember that changing the input will remove any edits that you made.  Functionality is planned to provide a means to lock and duplicate any edited content to avoid unintentionally loosing edits.


Field Selection
---------------

The Field Selection settings will dictate what field tags are applied to the search query so that the user can designate the fields they want to search.  Currently there are limited Field Tag options, namely, Term Fields and the Live/Dead status of applications/registrations.  The Field Tags are applied consistently as the Query Builder is intended to search the entirety of the input with the same settings.

Term Fields
+++++++++++

Live/Dead Field
+++++++++++++++

Settings Header
---------------

The Settings Header appears in the Top Right of the User Interface, but only when there is "Literal Element" input. 

Reset
+++++

The Reset button clears all content and reset the "Literal Element" input.  You can just delete all input as well.  This will not reset any changes made in the Settings Header or Field Selection sections, but will delete any user edits in the editable pattern matching.  A warning will appear in case you accidently hit the reset button to cancel the command.

Toggle Replacement View
+++++++++++++++++++++++

The Toggle Replacement View button will toggle the side-by-side vertical display that breaks down the characters of the user input and how the application is providing pattern matching for the characters.  This allows the user to more easily identify and be able to modify the editable input if the automatic input is not desired.  However, a user may want a more streamlined experience if they are familiar with the syntax and want a more streamlined interface.

Character Set (Char Set)
++++++++++++++++++++++++

The Character Set drop down is intended to give the user options to set the automatic pattern matching.  This is an initial iteration of this feature and it will likely change to be more flexible in future versions.  Currently, there are three options with the "MEDIUM" option recommended.  The "STRICT" option handles vowels and certain character combinations with more exact pattern matching that is the closest option to the original input.  The "LOOSE" option treats vowels as optional and provides very broad pattern matching.

Pattern Matching Table
----------------------

Element Display
+++++++++++++++

Replacement View Section
++++++++++++++++++++++++

**Characters Column**

**Replace Column**

Pattern Matching (Editable with Validation)
+++++++++++++++++++++++++++++++++++++++++++


Search Line Table
-----------------

Line Number
+++++++++++

Query Display
+++++++++++++

Copy
++++

Select
++++++
