## Update Set 
* are used for Recording and moving configuration changes from one instance to another intance **stored in an xml file**.
* Keeping system properties private prevents settings in one instance from overwriting values in another instance.
### Tables Involved
* **Update Set (sys_update_set)**: Stores Update Sets
* **Customer Update (sys_update_xml)**: Stores all the customizations of a update set 
* **Update Versions** (sys_update_version): Stores changes of customizations and helps in comparision
## List
* A list displays a set of records from a table.

## Forms
* Display data in the content frame.
* Used to create, view or modify/update specific records in a table.
* shows the record fields on the basis of Access
* **Examples**: Incident form, Change form, Knowledge Form.
### Elements of a form
* **Form header:** Provides navigation tools and actions related to the record.
* **Fields:** Stores specific data about the record.
* **Sections:**	Groups related information on the form.
* **Related links:** Provides access to additional functions based on record type and system setup. Administrators can add related links to forms using UI actions.
* **Related lists:** Displays records in other tables that have relationships to the current record.
* **Embedded lists:** Allows for editing related lists without having to navigate away from the form.
* **Response time indicator:**	Appears at the bottom of some forms to indicate the processing time required to display the form.
## Form Designs
* A way to personalize form layouts, views ans sections.(drag and drop)
## Tables/Fields
* A table is a collection of records in the database. Each record corresponds to a row in a table, and each field on a record corresponds to a column on that table.
### Creating Tables
* Navigate to System Applications > Studio.
* Select your Application [ `NeedIt` in my Case ]
* Click Create Application File
* in Filter Search for **`Table`** or Select **`Data Model`** and then click `Create`.
* Configure the file options.
    * `Label`: NeedIt
    * `Name`: (This field value is automatically created.)
    * `Extends table`: Task
    * `Create module`: Selected (checked)
    * `Create mobile module`: Selected (checked)
    * `Add module to menu`: -- Create New --
    * `New menu name`: NeedIt
* Switch to the Controls section (tab) and configure the controls:
    * `Auto-number`: Selected (checked)
    * `Prefix`: NI
    * `Number`: 2000
    * `Number of digits`: 6
    * `Create access controls`: (This field must be selected for scoped applications.)
    * `User role`: (This field value is automatically created. Notice the syntax of the user role name.)
## Related Lists
## Reports
## Access Controls

