To annotate something as an entity:

1. Select it in the image with the drawing tools.
2. Click the __Add Tag__ button in the right sidebar. This will open the data model search dialog.

## Data Model Search Dialog

The dialog provides full-text search over all Enitity Classes in your data model. If you don't enter a search
query into the search field, the dialog will show the root classes in your model instead. 

<img width="651" alt="Bildschirmfoto 2024-01-09 um 12 21 57" src="https://github.com/rsimon/immarkus/assets/470971/16c52991-3c11-47af-b63d-10c26832e58d">

In the screenshot above, the data model has a single root class called __Main Object__. Clicking __Main Class__ will navigate down the hierarchy, and show three child classes - __Bridge__, __Wall__ and __Gate__. 

<img width="651" alt="Bildschirmfoto 2024-01-09 um 12 21 43" src="https://github.com/rsimon/immarkus/assets/470971/b79678b0-c647-4f6d-b55c-1acfdd59fba2">

You will also notice that __Main Object__ has now been picked as your current selection. This is indicated by the brown __Main Object__ label next to the search field. 

- Click the __Ok__ button at the bottom of the dialog if you want to tag your entity as a __Main Object__.
- Or navigate the data model hierarchy further, if you are looking for a specific child of __Main Object__.

In the example above, neither __Bridge__, __Wall__, nor __Gate__ have further children. Therefore, clicking one of them will instantly select it and tag your annotation as this entity. The annotation will adopt the selected type's color coding and show it's properties form in the sidebar.

<img width="1440" alt="Bildschirmfoto 2024-01-09 um 12 22 40" src="https://github.com/rsimon/immarkus/assets/470971/847a66cd-8a6d-4951-a595-ef41b2115441">

In case a class has further children, clicking it will make it the new selection, and the dialog will list it's child classes, respectively. 

### Search

Note that the text search field takes into account your current selection.

- If there is no current selection, you can search the entire data model. 
- If you an Entity Class is selected, you will search __only in this branch of the data model__, i.e. across the children of the selected class as well as their children and so on.

<img width="620" alt="Bildschirmfoto 2024-01-09 um 12 23 24" src="https://github.com/rsimon/immarkus/assets/470971/88a490ee-30df-4d4e-aaa6-008ec88f3fb3">

 
