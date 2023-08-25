# npm package test by Sithu

## steps
Step 1 :

### Initialize the package
```sh
npm init
```

### Link for local testing
Before you publish it, test it in local, for that in package directory, run this command
```sh
npm link
```

### Use that package in Local
```sh
npm link npm-package-test-sithu
```

### Login
You need to login before you publish it
```sh
npm login
```


### Publish
from the package folder, run it
```sh
npm publish
```

## Prefix it if unavaiable
in package.json file, prefix with username

```json
{
  "name": "@sithusoe/npm-package-test-sithu",
}
```

By default, if we publish it with namespace package, it will try to make it private.
So, We can make it public

```sh
npm publish --access=public
```

If we want to scope our package scoped by default when we initialize it, use
```sh
npm init --scope=sithusoe
```