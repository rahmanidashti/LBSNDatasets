# Data description

## The number of Users and Locations was 18737 and 32510
To reduce the file size and running time we have reduced the number of users to 5000 and the number of location do not changed. So, the user's
id is 0 to 4999, and the location's id is 0 to 32509.

## How is the files format?

> Gowalla_data_size:
number_of_users number_of_locations

> Gowalla_train
User_id Location_id Frequency

> Gowalla_test
User_id Location_id Frequency

> Gowalla_tune
User_id Location_id Frequency

> Gowalla_poi_coos
Location_id Latitute Longitute

> Gowalla_checkins
User_id Location_id Checkin_time