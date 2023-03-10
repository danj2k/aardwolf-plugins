# Danj's Aardwolf plugins
After more than 20 years away from the MUD development community, Danj has returned to activity on Aardwolf MUD and is pleased to present his latest plugins.

## Danj_StatViz
This plugin allows you to visualize the 6 base trained stats (STR, INT, WIS, DEX, CON, LUK) on a spider graph in a mini window.

![Screenshot of the stats visualization plugin](danj_statviz_screenshot_updated.png)

The gridlines represent percentages of the maximum you can currently train that stat to, as indicated by the output of `train`. Gridlines are displayed at 20% intervals.

* `sv on` turns it on and updates it from `train` output.
* `sv off` turns it off.
* `sv update` updates it from `train` output if you already have the mini window open.
* `sv help` displays help information.

It's my first attempt at a MUSHclient plugin, so there are undoubtedly things that do not work as expected or do not conform to MUSHclient or Aardwolf client package norms; if you come across one of these cases, please create an issue on this GitHub giving as much information as possible.

## Danj_DMAssist

This plugin intelligently manages the casting of curse and dispel magic (or dampening field if you have the Psionicist class). It's not automatic, it just keeps track of whether your curses and dispel magics have failed or succeeded and will not cast curse or dispel magic/dampening field again depending on the outcome.

* `dm` will attempt to curse and dispel magic (or dampening field) your current target. If you're not currently in combat, it returns an error.
* `dm <target>` will attempt to curse and dispel magic (or dampening field) the named target.

Although this is now working, there may still be some bugs, please report these in the Issues section on this GitHub giving as much information as possible.
