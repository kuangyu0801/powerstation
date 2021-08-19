
# Start

```
docker-compose up
```

access frontend in browser via http://localhost:4200
# Step 1: Requirements clarifications
- User can CRUD power station
- User can query with position

# Step 2: System interface definition
api/station:
GET
POST
UPDATE
DELTETE
api/link
POST

# Step 3: Back-of-the-envelope estimation
skipped


# Step 4: Defining data model

PowerStation
id INT
x INT
y INT
reach INT

linkQuery

linkResponse
string

# Step 5: High-level design
Classi 3-Tier
Front-End: Angular
Back-End: Spring
DataBase: MySQL

# Step 6: Detailed design

# Step 7: Identifying and resolving bottlenecks

The bottle neck is reading power station from database
- this is a read-heavy system
- try to cache! (cache strategy?)

# Other nice feature
