# CSRF

  - Check if the framework used by the app uses any kind of CSRF protection built in.
  - Remember that "Any application that accepts HTTP requests from an authenticated user without having some control to verify that the HTTP request is unique to the user's session.". Try to find requests that doesn't send any cookies or params that look like a csrf token.
  - Check how and by what endpoint the token is being generated. 
  - Check if the token is statefull (The token is stored somewere on the server) or is stateless (the token is validated using some kind of algorithm).
