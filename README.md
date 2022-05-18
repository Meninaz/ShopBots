### A user-friendly shop system for discord

## Add the bot to your server

- #### 1. Click on the link and grant the bot admin permissions
https://discord.com/api/oauth2/authorize?client_id=[botid]&permissions=8&scope=bot

- #### 2. Type =setup into any text channel on your discord server for the bot to perform the setup itself
- #### 3. Start to use the bot with =help

## Install the bot yourself

- #### 1. Install the requirements
```python
pip install -r requirements.txt
```
- #### 2. Fill out the config.json
- ##### 2.1 Fill the essentials out and test the connection using the included tool
```python
python configure.py
```
- #### 3. Start the discord-shop
```python
python discord-shop.py
```
## Usage
#### You must have the "Support" role on your server in order to use the bot.

- #### =help: Command Help
- #### =clear: Delete all messages in a channel
- #### =addcategory: Create a shop category
- #### =additem: Create a item
- #### React with ✏️ to a item to edit it.
- #### React with 🗑️ to a item to delete it.

## Contributing
#### Pull requests are welcome. For major changes, please open an issue upfront to discuss what you would like to change.

#### Please make sure to update tests as appropriate.
