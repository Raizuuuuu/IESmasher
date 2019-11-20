# Internet Explorer Smasher

Are you sick of Internet Explorer? Ever wonder why people still use this garbage? Fear not, this script will smash Internet Explorer users away!

## How to use

`<script src="IE11-smasher.js"></script>`

## How it works

Internet Explorer uses the native Windows dialog API to display alert dialogs. What this means is that the main window cannot be interacted with while an alert is active, and requests to the host system to show dialogs are queued and persist after the main window is closed.

![](output.gif)