<div dir="rtl">
<br>
نصب پکیج : 
</div>

```bash
npm install fs-extra --save
```

<div dir="rtl">
استفاده از پکیج : 
</div>

```javascript
const fse = require(‘fs-extra’);
```

<div dir="rtl">
نحوه کارکرد :
</div>

```javascript
// Async with promises: 
fs.copy('/tmp/myfile', '/tmp/mynewfile')
  .then(() => console.log('success!'))
  .catch(err => console.error(err))
 
// Async with callbacks: 
fs.copy('/tmp/myfile', '/tmp/mynewfile', err => {
  if (err) return console.error(err)
  console.log('success!')
})
 
// Sync: 
try {
  fs.copySync('/tmp/myfile', '/tmp/mynewfile')
  console.log('success!')
} catch (err) {
  console.error(err)

```

<div dir="rtl">
متد ها :
</div>

```javascript
Async :

	•	copy
	•	emptyDir
	•	ensureFile
	•	ensureDir
	•	ensureLink
	•	ensureSymlink
	•	mkdirs
	•	move
	•	outputFile
	•	outputJson
	•	pathExists
	•	readJson
	•	remove
	•	writeJson


Sync :

	•	copySync
	•	emptyDirSync
	•	ensureFileSync
	•	ensureDirSync
	•	ensureLinkSync
	•	ensureSymlinkSync
	•	mkdirsSync
	•	moveSync
	•	outputFileSync
	•	outputJsonSync
	•	pathExistsSync
	•	readJsonSync
	•	removeSync
	•	writeJsonSync
```