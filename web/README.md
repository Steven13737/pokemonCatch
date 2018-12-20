## Demo for Let's Catch Pokemon

website http://35.229.119.69:8111/

## Gettting Started
#### Help you find the pokemon you want
Given an pokemon name with some features, you will get the location for the next appearance of this pokemon
![Pedict Pokemon Name](https://github.com/colirain/pokemonCatch/blob/master/web/src/predict_pokemon.png)
![result](https://github.com/colirain/pokemonCatch/blob/master/web/src/predict_pokemon_result.png)
#### help you find which pokemon will appear in a paticular location
Given an location with some features, you will find which pokemon will appear in this place
![Pedict Pokemon location](https://github.com/colirain/pokemonCatch/blob/master/web/src/predict_location.png)
![result](https://github.com/colirain/pokemonCatch/blob/master/web/src/predict_location_result.png)
#### Interactive Data Visualize
Take pikachu as an example, you can see the cities distribution in sortable bar chart
![](https://github.com/colirain/pokemonCatch/blob/master/web/src/city_1.jpg)
![](https://github.com/colirain/pokemonCatch/blob/master/web/src/city_2.jpg)

For all our data, you can see the distribution of cities, id and local time in hour. You can also choose one range in one of these three attributes and see the distributions of the other two attributes.

![](https://github.com/colirain/pokemonCatch/blob/master/web/src/time_city_id.jpg)
![](https://github.com/colirain/pokemonCatch/blob/master/web/src/time_city_id_2.jpg)

Enjoy!

### Directory Hierarchy

````
web
|--DataReload    
|	|--city_pokemon.py            # Export city-pokemon data for drawing       
|	|--time_city_pokemon.py       # Export time-city-pokemon data for drawing
|--src      # Demo Screenshots   
|--static 
|	|--/css    
|	|--/js    
|	|--model_latitue.pkl        
|	|--model_longtitude.pkl
| |--pikachu_city.csv
|	|--time_city.csv
| |--pokemonNumbers.csv         # Convert ID to name
|--server.py                    # flask main server file
|--templates  
|	|--index.html
|	|--pokemon_city.html          # Draw pokemon-city distribution in sortable bar chart  
|	|--time_city_id.html          # Draw time-city-id 
|--webpredict
| |--predict_id.ipynb           # Model Training and test predict
| |--predict_location.ipynb     # Model Training and test predict
+--  
````
### Prerequisites
python3.7
flask
flask-bootstrap
pandas
scikit-learn
d3.js
dc.js

