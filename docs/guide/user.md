## Making and Using a Character

### Signing up
`POST /sign-up`

Takes a JSON object comprised of a  `username` and `password`, and sets a token on your client.

```
.post('https://text-story-api.herokuapp.com/').send({
  username: 'newUsername',
  password: 'newPassword'
});
```

### Logging in
`POST /login`

Takes a JSON object comprised of a  `username` and `password` that already exist in the database, and sets a token on your client.

```
.post('https://text-story-api.herokuapp.com/').send({
  username: 'yourUsername',
  password: 'yourPassword'
});
```

### Logging out
`Get /logout`

Removes the local token associated with you account

```
.get('https://text-story-api.herokuapp.com/');
```
