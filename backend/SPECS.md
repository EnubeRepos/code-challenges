# Specs

## Import Worker

- You MUST implement a simple load process, that given a xlsx or csv file (see data folder), populates a SQL database.
- It MUST be writen in Go(lang).
- You can split the file into multiple tables.

## API

- You MUST implement a RESTful API
- You MUST implement pagination and filtering
- You MUST validate requests

### Auth/Management Endpoints

#### Login
```js
# request
POST /login
{
    "username": "",
    "password": ""
}

# response
Up to you
```

#### Register
```js
# request
POST /register
Up to you

# response
Up to you
```

#### Logout
```js
# request
POST /logout
Authorization: Bearer JWT

# response
Up to you
```

#### Create User
```js
# request
POST /users
Up to you

# response
Up to you
```

#### Get Users
```js
# request
GET /users

# response
Up to you
```

#### Get User by ID
```js
# request
Up to you

# response
Up to you
```

#### Update User
```js
# request
PUT /users

# response
Up to you
```

### Dashboard/Insights Endpoints

From now on you will be evaluated on your creativity in working with data previously imported into the database, filtering, paginating, returning data, etc.

- Dashboard/Insights endpoints **MUST be Authenticated**.

Some ideas:

- Resellers, Customers, Subscriptions names
- Cost by Day, Month