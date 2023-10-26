NPM does not recurse directories that match glob

glob: `"dist/!(__test__)"`


## NPM 9.8.1
```
npm notice
npm notice 📦  npm-files-glob@1.0.0
npm notice === Tarball Contents ===
npm notice 312B README.md
npm notice 0B   dist/index.js
npm notice 94B  package.json
```

## NPM 8.19.4
```
npm notice
npm notice 📦  npm-files-glob@1.0.0
npm notice === Tarball Contents ===
npm notice 273B README.md
npm notice 0B   dist/index.js
npm notice 0B   dist/util/util.js.js
npm notice 94B  package.json
```

