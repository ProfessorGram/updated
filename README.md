The Last updated (**updated**) module enables the display of information concerning when a node was last updated. Last updated information is always available in the Administrative GUI, and may also be made available in the User GUI.  Last updated functionality can be activated across an entire Content type, or on a Node-by-Node basis.  Extensive documentation regarding how to install, activate, configure, administer and use this module is available at:
https://github.com/backdrop-contrib/updated/wiki


## Installation
Please follow the official Backdrop CMS module installation workflow located at:  
https://backdropcms.org/guide/modules

## Administrative GUI Visibility
The day, date and time of the last node update appears as a read-only field in the "Authoring information" section of the node edit form.

## User GUI Visibility
Post activation, the day, date and time of the last node update appears as an addendum to the node creation information appearing by default in the User GUI.

## How To Expose Last Updated Information

### By Content Type
To control the display of Last updated information for an entire Content type in the User GUI, visit:

**Administration > Structure > Content types**

or 

**admin/structure/types**

To view a list of all available Content types.

Click **Configure** on the target Content type.  To activate Last updated functionality for the Content type, verify that the checkbox labeled ***Display last updated date*** in the ***Display settings*** tab is checked.  If it is, Last updated information should appear in the display of every instance of that Content type in the User GUI.

### By Individual Node
To control the display of Last updated information for an individual Node in the User GUI, visit:

**Administration > Structure > Content types**

or

**admin/structure/types**

To view a list of all available Nodes.  

Click **Edit** on the target Node.  To activate Last updated functionality for that individual Node, verify that the checkbox labeled ***Display updated date*** in the ***Publishing options*** tab is checked.  If it is, Last updated information should appear in the display of that individual Node in the User GUI.

## Issues
Questions, Bug reports and Feature requests can all be added to the Issue Queue for this module, located at:
https://github.com/backdrop-contrib/updated/issues

## License
This is Free and Open Source (FOSS) software.  Please refer to the LICENSE.txt file for a complete explanation of the licensing terms of this module.
