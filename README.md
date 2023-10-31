In this repo, I explore how to authenticate users in React. The web app I built in order to learn this is an Events web app. Logged in users can create, edit, and delete various Events they may be hosting. Non-logged in users can, however, still view the events. The UI reflects the current authentication status by showing either "Logout" or "Authentication" in the navigation bar. I manage users' authentication status with tokens, and set a 1 hour timeout to require users to log in every hour. Finally, we add route protection, so that only authenticated users can access certain routes.