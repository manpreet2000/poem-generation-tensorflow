----------------------
Poems generation
----------------------
Procedure: you need to pass starting of poem and number of characters.

    -text - To start poem; initial words. 
    -count - untill what words poem must generate. 
    

Class Hierachy

	|-------------------------|             |------------|
	|     Peom dataset        |-trained-on->|   LSTM     |
	|-------------------------|             |------------|
						       ^
						       |
						       |
						       |
						   Prediction
						       |  
						       |
						       |
						       |
						 |------------|
						 | text,count |
						 |------------|

