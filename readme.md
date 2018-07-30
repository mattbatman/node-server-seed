This repo is intended as a personal, basic, boilerplate node server with token authentication. It was created while following along with Stephen Grider's course on Udemy, Advanced React and Redux.

Note that the file `config.js` would need to be created to clone and use this repo as is. It would need to export an object with the key, `secret`, e.g.:

```
module.exports = {
  secret: 'randomhash'
};
```

It also requires MongoDB to be installed on your machine.
