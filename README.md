# RBLX Urban Dictionary API:
- A roblox module-script/api that gets you definitions for your word.

# How to use: 
- Firstly download the UrbanDictionaryAPI.rbxm file in this repository.
- Open roblox studio, create a new place.
- Publish it to roblox.
- Enable HTTPs in Game Settings > Security > Https Requests
- Drag the UrbanDictionaryAPI.rbxm file in the service called Workspace
- Create a script in Workspace with the following code:
> local UrbanDictionary = require(workspace.UrbanDictionaryAPI)
> local HelloWorldInfo = UrbanDictionary.get("hello world", 2)
> print(HelloWorldInfo.definition)

- Run the game, open output and it will print the definition.
- Change `hello world` to any word you want to define.
> There are more than `table`.definition:
- api.success
- author 
- current_vote
- defid
- definition
- example
- link
- sounds `-- this is a table of sounds {}`
- thumbs_up
- thumbs_down
- word
- written_on
