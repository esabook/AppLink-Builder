### Supported format

Dynamic link wrapper
original uri:
https://www.bareksa.com/path/path2?param

replacement:
<this-app-domain-name>/?<original-uri>


### Development

0. setup `firebase-cli`
1. `$ firebase login`
2. open at `.firebaserc` file, and change *project name* at `projects.default`
3. `firebase serve --host 0.0.0.0` // expose to machine address, accepts requests to any host


### Deploy
```
firebase deploy
```

### Related Guide
[https://firebase.google.com/docs/hosting/quickstart](https://firebase.google.com/docs/hosting/quickstart)
[https://firebase.google.com/docs/cli](https://firebase.google.com/docs/cli)
[https://firebase.google.com/docs/hosting/deploying](https://firebase.google.com/docs/hosting/deploying)
[https://firebase.google.com/docs/dynamic-links/create-manually](https://firebase.google.com/docs/dynamic-links/create-manually)