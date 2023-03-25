## UI-Customization-Salesforce-Admin
- Whenever we add a new field to the salesforce
- when we observe the student=>the details should be shown as the list=>all the fields one by one lined up into the column
- so,If you want some fields to the at starting and some fields at end(so,for this we need to rearrange the fields in here)
- If you want to modify the layout,Inorder to do that what I need do is,I need to know about the tools that are available to modify the UI without actually writing a single line of code
- Here in UI Customization, we go to know that how to modify the UI without writing single line of extra code
###  1.Page Layout
---------------------------
- Page Layouts controls two things
- 1.Detail page of a record
- 2.Edit page of a record
- Goto student=>Open student detail page so this is a detail page
- if you want to modify this one you can do with the page Layout
- If I create a new student ==>the page open ups there is edit page or edit the existing page is called edit page
- setup=>object manager=>student=>page layouts=>student layout=>click on it
- so,here if you want to rearrange the fields,it can be done by just draga nd drop
- so,now divide it to section or create new section
- Layout(you can choose 1 column or 2 column)
- Tab-key-order(whenever we submit a form we need tab-key order to go to the next field. So,you can select here, Whether it needs to go from left-right (or) top-down
- You can create as many sections as you needed
- There is one-way called as drag and drop called as pallet
- so,if you observe for formula fields  there is a lock
- Earlier with roll-up summary as well you see some there are only read only
- For Personal infromation one section,for contact into for related info rating related info
#### How many page Layouts can we createw
---------------------------------------------------------------------------------
- we can create as many as pagelayouts we need
- we can assign different-different ways down to different users
- Imagine that you are sitting on the registartion desk we want different page layout
- suppose for manager different page layout, for CEO different page layout
- Goto=>object=>page layout=>new 
- you can create a new page layout with the existing one and after creating you can assign based on page layout assignment
- 
- ### Search Layout
- When we search for a record in global search, by default it will display only standard record name field, when we click on look up icon it will display only          standard record name field in look up by default.
- But I want to display more number of fields when i do global search & and also i want to display more number of fields in look up. To display more fields use          searchlayouts.
- By using searchlayouts, we can customize which Sobject fields display for users in search results, look up dialogs, and the lists on custom tab home pages. 
- We can also specify a different set of fields to show in each searchlayout.
-  The settings apply to all users in your organization. And also we can specify which buttons to display in custom list views.
- How can we add fields to this layout?
- for standard objects: here i am giving example for Account object.
- Go to Setup -> Build -> Customize -> Account ->  click “SearchLayout” you will navigate to below screen.
- ![image](https://user-images.githubusercontent.com/72751737/227690408-70d39da9-e0b6-470b-9673-70b53445c70b.png)
- Then click on which type of layout you want to modify & move the available fields to selected fields. See the below screen for reference.
- ![image](https://user-images.githubusercontent.com/72751737/227690438-709392ec-7340-45af-81d4-9dadd7bee771.png)
- We can add or remove fields by using add & remove button and also we change the order of fields by using up & down arrows shown in above image.
#### Some important points:
– We can add up to 10 fields in this layouts.
–  These layouts don’t apply to campaign members, opportunity teams & account teams.
– We can’t remove unique identifying fields like Account Name or Case Number, from the search layouts. These fields must be listed first in the order.
– We can‘t add long text fields such as Description, Solution Details, or custom long text area fields.
– Formula fields are not available in search result layouts.

