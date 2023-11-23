# Prog_2_FinalReview

![Completed Application](Images/Complete.gif)

## Knowledge Need

All Controls
    - Give names to reference in your C# code
    - Add events
    - Change Text ( replace and append )
    - Get values

- TextBox
- Label
- Button
- Rich Text Box ( Run specifically )
    - Give run a name
    - How to append text
    - How to replace text
- ListBox and ComboBox
    - Items Source
    - Selected Index
    - On Selection Change event
- Lists
    - Create and initialize in local and global scope
    - Add files
    - Access individual elements
- Classes
    - Create classes in their own files
    - Fields
    - Constructors
    - Properties
    - Methods
    - Object in objects
    - How to override to strings
    - Checking for null
- CheckBox and RadioButton
    - How to get and respond to the selected value
- ListView
    - Items Source
        - Change source on load, and while application is running
    - Selected Index
        - Check if item is selected ( index != -1 )
    - On Selection Change Event

---
## Layout

![Layout](Images/Layout.png)

- Category change box
    - Combobox to hold category names
        - Has an on selection changed event
        - Displays todo items for category in listview
- Add New Category
    - Label, TextBox, Button
- Display ToDo Items
    - ListView
        - Has a selection changed event
        - Selected item information displays on rich text box to the right and text box info below.
- Task Name
    - Label, Textbox
- Description Box
    - Label
    - Rich Text Box
- High Importance
    - Check Box
- Time Sensitive
    - Check Box
- Complete and Not Completes
    - Radio Buttons, grouped together
- Add To List
    - Button
    - Event that adds new item to current category
- Update Selected Item
    - Button
    - Updates the currently selected item with the new information
- Clear Boxes
    - Clears all check boxes, text boxes, rich text boxes, sets the list view selection to -1, and sets radio button to not completed.
- Display Information
    - Rich Text Box

---

## Methods

