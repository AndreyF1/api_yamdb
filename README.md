# YaMDb service
## Key points
* Use views.
* Use JWT tokens for authentication.
* Unauthenticated users should have read-only access to the API. The exception is the /follow/ endpoint: access to it should be granted only to authenticated users.
* Authenticated users are allowed to modify and delete their content; otherwise, read-only access is granted.
* Adding new users via the API is not required.
* Own permission classes.
* Describing views, for some models to inherit from their own base viewset.
* Organize work with JWT tokens using the Djoser library.
