# Poke-maRt
One Stop Shop for all your Poke-Needs!

### 7 RESTful Routes
   VERB 		 | 		  PATH 		 |  	 DESCRIPTION
------------ | ------------- | -------------------
GET | api/v1/ | Home Page w/ Directory |
GET | api/v1/item/ | index of items |
GET | api/v1/item/:type | show page for selected item type |
GET | api/v1/item/:type/:model | show page for specific item model |
GET | api/v1/item/new | page to add new item |
POST | api/v1/item/ | post item to DB |
GET | api/v1/item/:item/:model/edit | page to edit a specific item |
PUT | api/v1/item/:item/:model | edit/update an item |
DELETE | api/v1/item/:item/:model | Delete item from DB |
