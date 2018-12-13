# Plotly-Project-Interactive-Map
...
You are given a dataset that contains the geo-codes for where customers shop and where customers live. You need to create (as best as you can) an interactive map that accomplishes the following: when a user clicks a shop, the customers who shop there are highlighted, lines are drawn from all the customers to that shop, or some such visual that helps the user to visualize where a store’s customers come from.



• Interpretation of the Map:

Green Circle : unclicked stores
Red Circle : clicked stores
Yellow Dot : unclicked custmers
Blue Dot : clicked customers
Green Lines : store -----> customers
Red Lines : customer -----> stores
Pop-up Window contains:
  how many customers came to a certain store;
  how many stores a certain customer visited;
  how many lines draw from which store;
  how many lines draw from which customer;

• Action:

Single click circle to see show lines.
Single click legend to show or hide objects.
Double click legend to see only the selected object.
Slide to zoom in for details or zoom out for whole world map.
Ckeck from Pop-up Window if it's the object you want to select before clicking. Hide other objects if you wish to click more accurately.
Once a store is clicked, it will change from Green Circle to bigger Red Circle. Green Lines will draw from store.
Once a custmer is clicked, it will change from Yellow Circle to Blue Circle. Red Lines will draw from custmer.
Legend's color and name will be updated on the right side of the map.
