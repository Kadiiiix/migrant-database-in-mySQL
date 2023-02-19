# migrant-database
a database system for migrant camps in a certain area, made in mySQL
Each Migrant is recorded with a unique ID, name which is composed of first,middle and last name, date of birth, the date they came to the camp, the country they came from, the bed they occupy recorded with the bed ,room and floor number (each migrant occupies one bed) ,and the camp they're staying at. If they have a child, the child's ID number will also be recorded with the name of one parent and the local school if they are attending.
Each camp has a unique ID number, a name, and reccord of the building it is in. Each camp has many migrants residing in it.
Each building has a unique ID, a name, a description and the location it is in is also recorded. Each building is for one camp only, and it is in one location, meaning it has one address.
Each location has unique ID number and its town, address and ZIP code are also recorded.
Each bed in camp is differentiated by its number, the floor it is on and the room it is in. Each camp has many beds.
Each staff member is recorded with a name (first, middle and last) and a unique ID. The staff that is recorded are cooks, cleaners, managers and janators (where cleaner's assigned floor and manager's degree are recorded). Each camp has many staff members working in it.
Each supply that comes to the camp (food, clothes etc) has a unique ID, a name and a description. A record of which supply is given to a migrant by staff members is also
recorded.
