# spike-publish-package

## Step before Publish

1. Setup file `.npmrc` in the file should look like this

```
@your-usernamep:registry=https://npm.pkg.github.com/
//npm.pkg.github.com/:_authToken=YOUR_PERSONAL_ACCESS_TOKEN
```

2. `npm install`

3. publish the package

```
npm publish
```

After run this step if you publish is successfully the response should be

response example follow as your username

```
npm notice total files: 4
npm notice
npm notice Publishing to https://npm.pkg.github.com with tag latest and default access
+ @your-username/spike-shared-package@1.0.0
```

## How to install on Other project

```
npm install @your-username/spike-shared-package
```
