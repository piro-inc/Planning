#server api routes
## User
POST / -- Generates a new user in the database with bcrypted password. Requires no auth.

GET /:id -- Returns JSON with username and email of user with the given id. Requires auth.

## Game
POST /:userid -- Generates a new game in the database with given props, associates game with given :userid param. Requires auth.

GET / -- Returns JSON array with all games. Requires no auth.

GET /:userid -- Returns JSON array with all games associated with :userid. Requires no auth.
