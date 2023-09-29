# To obtain free items, that are included in bundles.

## - Using `Javascript` in browser:
    
> Open browser > Inspect > Console > and paste:
   > ```
   > const gameId = prompt('Enter the game ID:');
   > const URL = `steam://install/${gameId}`;
   > window.open(URL, '_blank');     
   > ```
   > > Then press enter. The popup window will ask for a game ID .


## - Using `console`:

   >1. Press win + R
> 
   > 2. Paste `steam://install/game_id` 
> 
> > replace game_id


## - Using `Python`:

```
import webbrowser
URL = 'steam://install/'
game = input('enter id ')
webbrowser.open(URL + game)
```

            
