# cli-liquor-store

Liquor Store Pro is a command-line interface (CLI) application designed to streamline Supply Chain Management (SCM) for liquor stores. It facilitates efficient management of inventory, orders, suppliers, and logistics using an SQLite database for data storage and management.

### Features

- **Inventory Management**: Add, remove, and update liquor products with their respective quantities and prices.
## ADD
Add new items to the inventory with details such as name, price, and supplier.

python cli.py items add
Item name: Whiskey
Price: 50.00
Select Supplier (ID - Name):
1 - ABC Liquors
2 - XYZ Distributors
3 - Cancel
Supplier ID: 1

## UPDATE
Modify the details of existing items, including price and supplier information.

python cli.py items update
Item ID: 1
New item name: Premium Whiskey
New price: 60.00
Supplier ID: 1

## REMOVE
Delete items from the inventory when they are no longer available.

python cli.py items delete
Item ID: 1

## ORDER MANAGEMENT
### CUSTOMER
Process customer orders, track order status, and manage delivery schedules

python cli.py orders process

### PURCHASE
Create and manage purchase orders to replenish stock from suppliers.

python cli.py orders create_purchase

## ITEM MANAGEMENT
### UPDATE
Modify the details of existing items, including price and supplier information.

python cli.py items update
Item ID: 1
New item name: Premium Whiskey
New price: 60.00
Supplier ID: 1

### REMOVE
Delete items from the inventory when they are no longer available.

python cli.py items delete
Item ID: 1

## SUPPLIER MANAGEMENT
### SUPPLIER INFO
Maintain records of suppliers, including contact details and performance metrics.

### ADD
Add a new supplier to the system with contact information.

$ python cli.py suppliers add
Supplier name: ABC Liquors
Contact name: John Doe
Contact phone: 123-456-7890
Address: 123 Main Street

### UPDATE
Modify the details of an existing supplier.

python cli.py suppliers update
Supplier ID: 1
New supplier name: XYZ Distributors
New contact name: Kering Smith
New contact phone: 984-664-3210
New address: 456 Elm Street

### REMOVE
Delete a supplier from the system.

python cli.py suppliers delete
Supplier ID: 1


## AUTHOR
BY ELVIS KURIA