### `I. Steps to do:`
1. Clone code
2. Run the command: npm i
3. Run the project: npm run dev

#### `Note: In case all data is deleted (file db.json === empty), use file backup_db.json to retrieve data`

### `II.Endpoints (apis) used:`
 ```
1. Get all users:
GET /users

2. Get user by id
GET /users/:id

for example: GET /users/1

3. Create a new user
POST /users
body passed to object { email, name, name, password}

4. Update a users
PUT /users/:id
body passed to object { name, name}

5. Delete a user
DELETE /users/:id

Note that this is just fake data
```

