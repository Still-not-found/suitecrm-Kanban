# suitecrm

The logical development of the package Kanban board for the Opportunities module 

In this Release, the ability to display a list of any module in the form of a kanban board has been added.

The modules for which the kanban board will be displayed are configured in the administration (you can choose any modules)

You can also select the field by which the columns in the board will be built.

link to github: https://github.com/Still-not-found/suitecrm/
Installation
Before installation, you must make a backup copy of the system files!

To install, you need to download the latest version of the plugin from the link https://github.com/Still-not-found/suitecrm/

Then in SuiteCRM open the Module Loader (Administration → Module Loader)

Download package archive

Click the install button.

After installation, you need to make a Quick Repair and Rebuild (Admin → Repair ->Quick Repair and Rebuild)

Setting
After installing the package, go to Administration → Configuring modules for which the kanban board is available

On the settings page, select the modules for which the ability to display as a kanban board will be available.

After selecting the modules for which the ability to display as a kanban board will be available, when switching to these modules, a link will be available in the left panel to go to the board page or module settings (if the settings for the module are not saved for this user)
The first time you go to the Kanban board page, you go to the kanban board settings page for a specific module. The settings of each module are located in a separate tab, and require separate saving Modules for which the settings of the Kanban board are saved are colored green.
Setting up the field for selecting columns on the Kanban board
To select a field from the values of which columns will be formed on the Kanban board, specify this field in the Select field from the stages field (only fields of the enumeration type are displayed)

Customizing columns
Configuring speakers for a kanban board

To set the desired column sequence, set the sequence you need from top to bottom (will be converted to a sequence from left to right)


check the display colum checkbox to display the column on kanbandosk

check the display opportunity checkbox to display the record in the column (it is not recommended to check completed with success and canceled in the final columns)

Customizing header fields
Setting the fields that will be displayed in the card lining, if there are several fields, then they will be separated by the symbol -

Field for sorting cards on the board
Setting up the field by which sorting will be performed (Sorting will be reversed) in the kanban column of the board.


Board column height
Specifies the height of the board on the page

