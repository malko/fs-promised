# fs-promised

fs-promised is a node module to make file system access through promises.
It uses [d.js](https://github.com/malko/d.js) for as promises library just check to that project for more info about the returned interfaces.

## additional methods 
- fs.readJsonSync(filename, options)
- fs.readJsonPromise(filename, options)
- fs.writeJsonSync(filename, data, options)
- fs.writeJsonPromise(filename, data, options)
- fs.watchDeduped(filename, options, listener)