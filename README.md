# Pokémon Data

All this data is collected for you own personal projects, to help you to have some data example. If there is some issue or error, please, let me know. 

**Data 'Em All!**

## pokemon.csv

|column|type|definition|
|------|----|----------|
|name|text|Pokémon Name.|
|type_1|text|First type of the Pokémon.|
|type_2|text|Second type of the Pokémon, it can be null.|
|ability_1|text|First ability of the Pokémon.|
|ability_1_is_hidden|boolean|True if the first ability of the Pokémon is a hidden ability.|
|ability_2|text|Second ability of the Pokémon. It can be null.|
|ability_2_is_hidden|boolean|True if the second ability of the Pokémon is a hidden ability. It can be null.|
|ability_3|text|Third ability of the Pokémon. It can be null.|
|ability_3_is_hidden|boolean|True if the third ability of the Pokémon is a hidden ability. It can be null.|
|height|number|Pokémon height.|
|weight|number|Pokémon weight.|
|stat_hp|number|Pokémon HP stat.|
|stat_attack|number|Pokémon HP stat.|
|stat_defense|number|Pokémon HP stat.|
|stat_spattack|number|Pokémon HP stat.|
|stat_spdef|number|Pokémon HP stat.|
|stat_speed|number|Pokémon HP stat.|
|sprite|text|Pokémon Sprite url.|

## moves.csv

|column|type|definition|
|------|----|----------|
|name|text|Move name.|
|accuracy|number|Accuracy percentage. If it has -1, it means it can not fail.|
|effect_chance|number|Percentage to trigger the effect.|
|pp|number|Power point.|
|priority|number|Priority modifer.|
|power|number|Move Power.|
|class|text|Physical, status or special.|
|type|text|Move type.|
|crit_rate|number|Critical Rate.|
|drain|number|Percentage of drain.|
|flinch_chance|number|Percentage for flinch.|
|healing|number|Percentage of healing.|
|max_hits|number|Maximmum number of hits.|
|min_hits|number|Minimmum number of hits.|
|max_turns|number|Maximmum number of turns.|
|min_turns|number|Minimmum number of turns.|
|stat_chance|number|Percentage to trigger the effect about stat change.|
|effect|text|Effect text.|


## abilities.csv

|column|type|definition|
|------|----|----------|
|name|text|Ability name.|
|effect|text|Ability effect. It can be null.|

## learning.csv

|column|type|definition|
|------|----|----------|
|Pokémon|text|Pokémon name.|
|move|text|Move that can learn the Pokémon.|
|level_learned_at|number|Level at which the Pokémon can learn the move.|
|learn_method|text|Method to learn the move.|
|game|text|Pokémon game.|


---

All this information is from [PokeApi](https://pokeapi.co).
Pokémon and Pokémon character names are trademarks of Nintendo.
Some applications with Pokémon Data will be added on this repository.

