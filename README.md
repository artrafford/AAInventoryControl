# AAInventoryControl

DB Name = bot_games

Database Tables, Columns, type

inventory
	* item_id - int
	* in_stock - int
	* inventory_count - int

inventory_control
	* item_id - int
	* item_name - varchar
	* threshold - int
	* priority - int
	* default_shipping_method - varchar
	* max_inventory - int

order_table
	* order_id - int
	* order_status - varchar
	* item_id - int 
	* confirmation_number - varchar
	* quantity - int
	* cost - decimal
	* order_date - datetime

shipping_addresses
	* address_id - int
	* address_name - varchar
	* address_1 - varchar
	* address_2 - varchar
	* city - varchar
	* state - varchar
	* zip_code
