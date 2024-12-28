The Last updated (**updated**) module enables the display of information concerning when a node was last updated.  This information is always available in the Administrative GUI, and can be optionally made available in the User GUI via settings appearing in the Administrative GUI.  Last updated functionality can be activated at the *Content type* level or at the individual Node level.  More comprehensive documentation regarding this module is available at:
https://github.com/ProfessorGram/updated-1.x-1.0.0/wiki


## Installation
This module does not require a custom installation.  Follow the official Backdrop CMS module installation workflow located at:  
https://backdropcms.org/guide/modules

## Administrative GUI Visibility
Post-installation, the day, date and time of the last node update always appears as a read-only field in the "Authoring information" section of the node edit form.

## User GUI Visibility

### By *Content Type*
To control the display of Last updated information for an entire Content type, visit:

**Administration > Structure > Content types**

or 

**admin/structure/types**

To view a list of all available Content types. Next, click **Configure** on a target Content type and verify that the checkbox labeled ***Display last updated date*** in the ***Display settings*** tab of the Content type edit form is checked.  If it is, Last updated functionality is enabled for every instance of that Content type.

### By Individual Node
To control the display of Last updated information for an individual node, visit:

**Administration > Structure > Content types**

or

**admin/structure/types**

To view a list of all available Nodes.  Next, click **Edit** on a target Node and verify that the checkbox labeled ***Display updated date*** in the ***Publishing options*** area of the node edit form is checked.  If it is, Last updated functionality is enabled for that individual Node.

## Issues
Questions, Bug reports and Feature requests can all be added to the Issue Queue for this module, located at:
https://github.com/backdrop-contrib/updated/issues

## License
This is Free and Open Source (FOSS) software.  Please refer to the LICENSE.txt file for a full discussion the licensing terms of this module.
