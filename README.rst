Solarized-Light is a variant of the Skylight and Skylight-Dark style for the Textual IRC client.

* Skylight: https://github.com/mintchaos/Skylight
* Skylight-Dark: https://github.com/idangazit/Skylight-Dark
* Textual IRC: http://www.codeux.com/textual/

To install dump this folder into ~/Library/Application Support/Textual/Styles

It looks like this: 

.. image:: http://dl.dropbox.com/u/407293/Screen%20shot%202011-07-07%20at%2011.07.10%20AM.png


Important notes and warnings:
============================

You need be using the default time stamps in this format:
[%m/%d/%Y -:- %H:%M:%S]

At this point Textual uses the the timestamp as set in the preferences for the
logs. This theme is opinionated about time stamps and edits them via JS but
expects them to start in this format.

Also note that Skylight screws with the DOM and switching to skylight or from
Skylight and other styles may require a restart or some other form or
resetting the current channels.



Tricks
======

* Usernames and messages are aligned.
* Multiple messages from the same user only display the username for the first 
  message.
* Time stamps are simplified down and only shown when the time changes.
* Dates are shown in a nice conversation marking badge, but again only when 
  they change.
* Clicking on a username will highlight all messages from that user in the 
  active channel. Clicking again will clear, clicking on someone else with 
  switch.



Props
=====

This style contains some code from the Simplified style that ships with Textual & contains some ideas from the Simplified theme for Linkinus by "Cowboy" Ben Alman (http://benalman.com/). 

Scripts.js contains a copy of jQuery by John Resig

Original Skylight by Christian Metts.
