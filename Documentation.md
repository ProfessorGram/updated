The Last updated module displays information about the last time a node was updated as an addendum to node creation information. Post-activation, node update information is always available in the Administrative GUI, and can be made visible in the User GUI.

## Administrative GUI Visibility
### Configuration By Content Type
Last updated functionality appears in the Administrative GUI as a read-only **Last updated** field in the **Authoring information** tab of the Node edit form.

For this information to appear, the Content type of the Node must have Last updated functionality activated. 

To activate Last updated functionality for a Content Type, visit:

**Administration > Structure > Content types**

or 

**admin/structure/types**

A list of Content types will be presented.

- Click **Configure** on the Content Type for which Last updated is to be configured
- Scroll down to the bottom of the edit form
- Click on the **Display settings** tab.  
- Ensure the **Display author and date information** checkbox is checked
- Ensure the **Display last updated date** checkbox is checked
- Click **SAVE CONTENT TYPE**

The **Last updated** field should now appear in the **Authoring information** tab of the edit form for each Node of that Content type.

### Configuration By Node
To control whether or not Last updated information appears along with creation information regarding a Node displayed in the User GUI, visit:

**Administration > Content**

or

**admin/content**

A list of Nodes will be presented.

- Click **Edit** on the Content Type for which Last updated is to be configured
- Scroll down to the bottom of the Node type edit form
- The ***Publishing options*** tab should be displayed.
- Ensure **Display author and date information** is checked
- Look for the **Additional options** section
- Ensure the **Display last updated date** checkbox is checked
- Click **SAVE**

**Last updated** information should now appear as an addendum to the Node author and creation information displayed in the User GUI.

## Issues
Questions, Bug reports and Feature requests can all be added to the Issue Queue for this module, located at:
https://github.com/backdrop-contrib/updated/issues

## License
This is Free and Open Source (FOSS) software.  Please refer to the LICENSE.txt file for a complete explanation of the licensing terms of this module.
