The Last updated (**updated**) module enables the monitoring of when a node was last updated.  This information is always made available in the Administrative GUI, and can be optionally exposed within the User GUI via settings made present in the Administrative GUI.  Last updated functionality can be applied at the *Content type* level or at the individual Node level.  More comprehensive documentation regarding this module is available at:
https://github.com/ProfessorGram/updated-1.x-1.0.0/wiki


## Installation
This module does not require a custom installation workflow.  Simply follow the official Backdrop CMS module installation workflow located at:  
https://backdropcms.org/guide/modules

## Administrative GUI Visibility
Post-installation, the day, date and time of the last node update always appears as a read-only field in the "Authoring information" section of the node edit form.

## User GUI Visibility

### By *Content Type*
To control the display of Last updated information for an entire Content Type, visit:

**Administration > Structure > Content types**

or 

**admin/structure/types**

Click **Configure** on the target *Content type* and verify that the checkbox labeled ***Display last updated date*** in the ***Display settings*** tab of the Content type edit form is checked.  If it is, Last updated functionality is enabled for that Content type.

### By Individual Node
To control the display of Last updated information for an individual node, visit:

**Administration > Structure > Content types** [this is wrong]

**admin/structure/types** [this is wrong]

To view a list of all available Nodes.

Click **Edit** on the target Node and verify that the checkbox labeled *Display updated date* in the *Publishing options* area of the node edit form to enable Last updated functionality for that individual Node.

## Issues
Questions, Bug reports and Feature requests can all be added to the Issue Queue for this module, located at:
https://github.com/backdrop-contrib/updated/issues

## License
This is Free and Open Source (FOSS) software.  Please refer to the LICENSE.txt file for a full discussion the licensing terms of this module.
