This projet utilises middleware to control an async request for user details 

The axios library is used to make an api request (to get user data from an api) which returns a promise.

The middleware created stops the payload being passed to the reducer functions until the promise has resolved and data received.
