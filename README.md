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
npm notice
npm notice 📦  @ong-tanat-jak-nxz-group/spike-shared-package@1.0.0
npm notice Tarball Contents
npm notice 24B README.md
npm notice 468B package.json
npm notice 137B src/index.js
npm notice 960B src/logger.js
npm notice Tarball Details
npm notice name: @ong-tanat-jak-nxz-group/spike-shared-package
npm notice version: 1.0.0
npm notice filename: ong-tanat-jak-nxz-group-spike-shared-package-1.0.0.tgz
npm notice package size: 912 B
npm notice unpacked size: 1.6 kB
npm notice shasum: b23ea6f2969f071baed420b4f88c16f7f2d1ebb5
npm notice integrity: sha512-UQowB8tocO4aZ[...]k2DlMb3Hs2+mA==
npm notice total files: 4
npm notice
npm notice Publishing to https://npm.pkg.github.com with tag latest and default access
+ @ong-tanat-jak-nxz-group/spike-shared-package@1.0.0
```
