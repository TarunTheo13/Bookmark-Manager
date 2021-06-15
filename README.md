# Bookmark Manager

## User Stories

```
As a user,
So that I can return to websites of interest
I want to view a list of bookmarks.
```

## Domain Model

<img width="401" alt="domain model" src="https://github.com/TarunTheo13/Bookmark-Manager/blob/main/images/Screenshot%202021-06-14%20at%2014.58.48.png">

### To set up the database

Connect to `psql` and create the `bookmark_manager` database:

```
CREATE DATABASE bookmark_manager;
```

To set up the appropriate tables, connect to the database in `psql` and run the SQL scripts in the `db/migrations` folder in the given order.

### To run the Bookmark Manager app:

```
rackup -p 3000
```

To view bookmarks, navigate to `localhost:3000/bookmarks`
To view bookmarks, navigate to `localhost:3000/bookmarks`.
