# Please follow the following steps

# 1)
# Run the following command to instal the dependencies
composer install

# 2)
# To start the project run the following command
php spark serve

# 3)
# To convert the CSV into the JSON and XML run the following command
# Make sure PHP is installed on the server and available on $PATH
# The example file (example.csv) can be found on the root of the project
cd public
php .\index.php convert_csv

# 4)
# Use the following urls to retrieve data from rest api
# JSON responses
http://localhost:8080/
http://localhost:8080/?name=Atlantis%20The%20calm
http://localhost:8080/?discount_percentage=10
# XML responses
http://localhost:8080/?type=xml
http://localhost:8080/?name=Atlantis%20The%20calm&type=xml
http://localhost:8080/?discount_percentage=10&type=xml