# Vk_bot
**Vk bot** for community
 
This bot is written for informational purposes with the **Vk_api** library and the **PostgreSQL** database (PonyORM)

For normal operation, you need:

- Add your group's token to **settings.py**
- Change or create a new **settings.py.default** as **settings.py**
- Download and install **PostgreSQL** (if **PyCharm** is used, open the database to the right of the code and create a connection)
- Enabling and all the work of the bot goes through bot.py
- All **Events** are processed and recorded in **logs_boot.log**
 
You also need to create patterns for **logging** in **Ideolog**:

Message pattern: ^(\d{2}-\d{2}-\d{4}\s\d{2}:\d{2})\s(\w*)\s(.*)$

Time format: dd-MM-yyyy HH:mm
