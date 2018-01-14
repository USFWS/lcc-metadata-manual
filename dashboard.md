# Dashboard

## Overview

The mdEditor application is designed using a two-pane layout. The left _**sidebar**_ \(1\) provides the primary navigation showing a list of **Metadata Records**, **Contacts** and **Data Dictionaries**. The right pane displays a context-sensitive _**main menu **_\(2\) at the top, a primary _**editor region **_\(3\) below that displays and allows for the editing of a selected object and a** **_**status bar **_\(4\) at the very bottom of the display.

![](/assets/mdEditor_areas.png)

---

### Basic Navigation

### Sidebar

The left sidebar displays the various components of the current metadata record set. The components are arranged by type in a series of expandable panels that group the metadata, contact, and data dictionary records.

![](/assets/mdEditor_logo_32.png)   Select the **mdEditor **logo to toggle the display of the sidebar.

![](/assets/symbol_question-circle_16.png) Select the **help icon** to display context-sensitive help. Click again to view the object groups.

![](/assets/symbol_plus_16.png) Select the **plus icon **to add a new record to an object group.

![](/assets/symbol_list_16.png) Select the **list icon** to display a searchable list of individual objects in the editor region.

![](/assets/symbol_angle-down_16.png) Select the **angle-down icon** to expand a group panel and display a list of records in the sidebar.

![](/assets/symbol_angle-up_16.png) Select the **angle-up icon **to collapse a group panel and to hide all associated records.

### Main menu

The main menu contains several standard menu items that apply to areas of the mdEditor, and content-specific menu items that will vary depending upon the type of record that is active.

#### Standard menu items

![](/assets/symbol_dashboard_16.png) **Dashboard**. Return to main dashboard.

![](/assets/symbol_sign-out_16.png) **Export**. Export the metadata record set in mdJSON format. The mdJSON file can be used to share your metadata with others or to provide a backup. [See Export](/export.md).

![](/assets/symbol_sign-in_16.png) **Import**. Import a mdJSON file into the editor. [See Import](/import.md).

![](/assets/symbol_cog_16.png) **Settings**. Customize the editor settings. [See Settings](/settings.md).

### Editor region

The editor region will display information based on the type of object that is currently selected. Selecting a **list icon** \(![](/assets/symbol_list_16.png)\)will display all of the records contained in the associated object \(metadata, contacts or dictionaries\) in the editor region. Selecting a record will display record specific information and allow the record to be edited.

### Status Bar

The status bar displays various informational messages, such as whether the [Auto Save](/settings.md) feature is on or off.

# Right Vertical Menu

The right vertical menu allows for general manipulation of records and contacts. Available options differ depending on whether the item is being viewed or edited.

---

### General Options

_Options available when viewing or editing_

* **Copy**: The copy button makes a duplicate of a record or contact.
  > ![](/assets/NoteSmall.png) Making a copy will generate a new ID for the copied record and be named “Copy of …”. All the other info will remain the same including associations. The “metadata identifier” is NOT copied but any identifiers in the main citation WILL be copied, including any ScienceBase IDs.
* **Delete**: The delete button will completely delete the record or contact.

  > ![](/assets/BestPracticeSmall.png)**Best Practice**: Make a backup of your record or contact before deleting. Consult the [**Export**](/export.md)** **section of this manual to learn how to make a backup.

  ---

### Viewing Options

_Options available when viewing_

![](/assets/right_vertical_menu_view.png)

Viewing options include everything mentioned above along with an **Edit **button. This button will allow you to begin editing your item.

---

### Editing Options

_Options available when editing_

![](/assets/right_vertical_menu_edit.png)

Editing options include the above options along with the following:

* **Save**: Used to save changes. 
  > ![](/assets/NoteSmall.png) Save can only be used if auto-save is turned off. Consult the [**Settings**](/settings.md)** **section of this manual for more information.
* **Cancel**: Used to undo changes that have not yet been saved.



