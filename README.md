#Virtual Closet#

* This service is a digital closet for users to record their articles of clothing. Article of clothing are added by users, assigned a unique identifier, and are then globally accessible by all other users. In order to add an item into the global and their personal collection, the user must identify, at a minimum, the title, designer, and color. Users will want to search the collection based on any number of factors that include the type of article, designer or color.

#ID Attribute Values#
* Add Item: Add article of clothing to your collection. Applied to a FORM to create a new entry.
* Add New to The Inventory: Add a new article to the global inventory.
* Search My Closet: Query used to locate an item in your closet. Applied to a FORM to search.
* Search The Inventory: Query the global inventory collection to locate an item. Applied to a FORM for search.
* Update Item: Use a FORM to update an existing item in your closet.

#Class Attribute Values#
* SearchCloset: Search for an item in your personal closet; applied to a FORM tag.
* SearchInventory: Search the global inventory collection; applied to a  FORM tag.
* designer: Name of the designer
* color: Color of the item
* title: Title of the item
* description: Details of the item
* allitems: The list of all items in the global inventory collection
* myitems: The list of all items in the user's closet

#Name Attribute Values#
* item[ID]: Unique identifier for each item
* item[title]: Brief title for the item; applied to an INPUT[text] element
* item[designer]: The designer of the item; applied to an INPUT[text] element
* item[color]: The color of the item; applied to an INPUT[text] element
* item[description]: Description of the item; applied to a TEXTAREA element

#Rel Attribute Values#
* Item: Link to a particular item; applied to an 'a href' tag
* Designer: Link to a designer's home page; applied to an 'a href' tag
* Closet: Link to the personal closet home page; applied to an 'a href' tag
