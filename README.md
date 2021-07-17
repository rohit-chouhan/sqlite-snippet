<p align="center">
<img width="150" src="https://www.vectorlogo.zone/logos/sqlite/sqlite-ar21.svg">+<img width="150" src="https://www.vectorlogo.zone/logos/python/python-ar21.svg"><br>
Simle Easy SQLite Snippet for  Python, Developed by <a href="https://rohitchouhan.com">Rohit Chouhan</a>
</p>


## Install form Here
https://marketplace.visualstudio.com/items?itemName=rohit-chouhan.sqlite-snippet

| Prefix   |Description   |
| ------------ | ------------ |
|  sl-import | import sqlite3   |
|  sl-createConnection, sl-createDb | create connection code   |
|  sl-createTb | create table code   |
|  sl-select | retrive data code   |
|  sl-selectAll | retrive all data code   |
|  sl-insert | insert data code   |
|  sl-update | update data code   |
|  sl-updateAll | update all data code   |
|  sl-delete | delete data code   |
|  sl-deleteAll |delete all data code   |

#### - Example
```python
#input
	sl-select
	
#output
	c = conn.cursor()
	c.execute("SELECT * FROM table WHERE column='value'")
	rows = c.fetchall()
	for row in rows:
		print(row)
```
