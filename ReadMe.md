##

To get all the data of users just simply make a get request at https://yellow-frog-kit.cyclic.app

To get the data of specific user then pass the username of that person in the params while making the get request at https://yellow-frog-kit.cyclic.app

To post the data of a user then make a post request at https://yellow-frog-kit.cyclic.app
The body should have this schema - {username:String, score:Number}

To update the score data of a user, make a PATCH request at https://yellow-frog-kit.cyclic.app.
The body should have this schema: {username: String, score: Number}.
