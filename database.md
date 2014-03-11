# Database Progress

## Known Issues
* classes for 1975 data mostly missing (~72,000)
* titles truncated beyond 256 characters -- needs schema adjustment

## March 11, 2014
-----------------

### Production
*grant*
* fixed error in flow where not all inventor records were linked to locations in the `inventor_location` table. 

## March 10, 2014
-----------------

### Production
*grant*
* currently backing up

*application*
* currently backing up

### Development
*grant*
* needs assignee disambiguation
* needs location links to disambiguated records
* awaiting joint grant/app inventor disambiguation

*application*
* need to adjust claim foreign keys into the application table
* needs assignee disambiguation
* needs location links to disambiguated records
* awaiting joint grant/app inventor disambiguation