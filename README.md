# ppua5262
Our data set is scraped from Google Places API. The description of the variables is below:
Place_id: a textual identifier that uniquely identifies a place
Name: contains the human-readable name for the returned result
Vicinity: lists a simplified address for the place, including the street name, street number, and locality, but not the province/state, postal code, or country
Tag_X (where X=1,...,10): string containing place details restricted to 100 different tags such as health, zoo, car_dealership, and lawyer
X: contains longitude coordinate, expressed in degrees
Y: contains latitude coordinate, expressed in degrees
Place_geog: it represents values which connect geographical coordinates and block_ID in the dataset
Place_geog_type: the place_geog value for each location is represented by 2 values: the land parcel ID (Ln_P_ID) and the Location ID (LOC_ID)
Blk_ID_10: numeric variables with 15 digits which contained the corresponding State, County, Tract and Block ID's
State: the first 2 digits of the Blk_ID_10 variable represents the State code.
County: the 3rd digit to the 5th digit of the Blk_ID_10 variable represents the County code.
Tract_Group: the 6rd digit to the 11th digit of the Blk_ID_10 variable represents the Tract_Group code.
Block_Group: the 12th digit to the 15th digit of the Blk_ID_10 variable represents the Block_Group code.
Area: String describing the name of the area/city derived from 'vicinity'
Street: String describing the name of the Street derived from 'vicinity'
Bucket_vicinity: The specific area either ‘Boston’, ‘Greater_MA’, ‘Greater_Boston’, ‘Outside_MA’, or ‘N/A’ based on the city or part of city listed in the vicinity column. 
Category_group: String generalizing the information in Tag_1 column, groups the 100 possible tags into broader categories such as Entertainment, Education, and Parking_Transportation

