 Project description
 *Project Name:* Warehouse Inventory System

### *Overview:*

This is a simple program for managing warehouse inventory. It allows users to:

1. Add new items to the warehouse.
2. Remove items from the warehouse.
3. Update the quantity of existing items.
4. Search for items by ID or by name.
5. Display all items in the inventory.

This program helps warehouse staff *keep track of stock and item details* easily.

---

### *File Descriptions*

*1. Item.java*

* Represents a single warehouse item.
* Stores the *ID, Name, Quantity, and Price* of the item.
* Contains *getter methods* to access values and a *setter* to modify quantity.
* The toString() method is used to *display item information clearly*, e.g., I001 | Pen | Qty: 10 | Price: 25.5.

*2. Inventory.java*

* Maintains a list of all items using *ArrayList<Item>*.
* Includes the following methods:

  * addItem() → Adds a new item to the list.
  * removeItem() → Deletes an item by ID.
  * updateQuantity() → Updates the quantity of an item by ID.
  * searchById() → Finds an item using its ID.
  * searchByName() → Finds an item using its name.
  * displayAll() → Shows all items in the inventory.
* Uses *simple for-loops* to go through the list and perform actions.

*3. Warehouse.java*

* The main program containing a *menu-driven interface*.
* Allows users to choose actions: Add, Remove, Update, Search, Display, or Exit.
* Uses *Scanner* to take input from the user.
* Calls the appropriate *Inventory methods* to execute the selected task.

---

### *How to Run the Program:*

1. Compile the program:

   
   javac Warehouse.java
   
2. Run the program:

   
   java Warehouse
   

---

### *Example Output:*

```
--- Warehouse Menu ---
1. Add Item
2. Remove Item
3. Update Quantity
4. Search by ID
5. Search by Name
6. Display All
0. Exit
Enter choice: 1
Enter ID: I001
Enter Name: Pen
Enter Quantity: 10
Enter Price: 25.5
Item added!
