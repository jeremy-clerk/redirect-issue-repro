# Steps To Repro

- Copy .env.local.example
```bash
cp .env.local.example .env.local
```
- add publishableKey & secret key
- sign up/in using oauth
- sign out
- click the sign-in button on the home page
- click sign up on the modal
- sign in via oauth
- you will be redirected to accountportal/user

Expected to redirect to "/" as this is set on the sign-in button props.