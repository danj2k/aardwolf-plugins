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

Please report any problems by creating an issue on this GitHub giving as much information as possible. Screenshots may also be helpful.

## Danj_DMAssist

This plugin intelligently manages the casting of curse and dispel magic (or dampening field if you have the Psionicist class). It's not automatic, it just keeps track of whether your curses and dispel magics have failed or succeeded and will not cast curse or dispel magic/dampening field again depending on the outcome.

* `dm` will attempt to curse and dispel magic (or dampening field) your current target. If you're not currently in combat, it returns an error.
* `dm <target>` will attempt to curse and dispel magic (or dampening field) the named target.

Please report any problems by creating an issue on this GitHub giving as much information as possible. Screenshots may also be helpful.

## Danj_SLALOM

### SLopes Assist: Leader Observation Machine

SL.A.L.O.M. is a plugin to help followers navigate the fast-paced world of Icefall Slopes. (If you're the tank, this plugin is not for you!)

* Not sure what to do or where to go? Type `sla` and the plugin will either execute a command or tell you what you should do.
* Leader has left the room? Type `sla` to follow them.
* `sla leader <charactername>` to set the expedition leader.
* `sla <direction>` if the leader declares a slope. But don't worry if they don't, SL.A.L.O.M. can follow them anyway.

Please report any problems by creating an issue on this GitHub giving as much information as possible. Screenshots may also be helpful.
