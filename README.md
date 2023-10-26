NPM does not recurse directories that match glob in v9 & v10

glob: `"dist/!(__test__)"`

## npm v10.2.1
```
npm-files-glob git:(main) ✗ npm -v && npm pack
10.2.1
npm notice
npm notice 📦  npm-files-glob@1.0.0
npm notice === Tarball Contents ===
npm notice 897B README.md
npm notice 0B   dist/index.js
npm notice 94B  package.json
```

## NPM v9.9.0
```
➜  npm-files-glob git:(main) ✗ npm -v && npm pack
9.9.0
npm notice
npm notice 📦  npm-files-glob@1.0.0
npm notice === Tarball Contents ===
npm notice 961B README.md
npm notice 0B   dist/index.js
npm notice 94B  package.json
```

## NPM v8.19.4
```
npm-files-glob git:(main) ✗ npm -v && npm pack
8.19.4
npm notice
npm notice 📦  npm-files-glob@1.0.0
npm notice === Tarball Contents ===
npm notice 934B README.md
npm notice 0B   dist/index.js
npm notice 0B   dist/util/util.js.js
npm notice 94B  package.json
```

