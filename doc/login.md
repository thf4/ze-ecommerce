# Login

> ## Success Case

1. ✅ Receive request **POST** router /login
2. ✅ Validated email and password user data.
3. ✅ Validated email.
4. ✅ Validated password.
5. ✅ Create user account.
5. ✅ Return 200 with user token authentication.

> ## Exceptions

1. ✅ Return error 404 with api doesn't exist.
2. ✅ Return error 401 when user doesn't have account.
3. ✅ Return error 400 when user try to write your email with characters incomum.
4. ✅ Return error 400 when user write wrong password.
5. ✅ Return error 500 when user try to create account and service doesn't work.
6. ✅ Return error 500 when api return error to create a token.