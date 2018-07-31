<div dir="rtl">
نصب پکیج : 
</div>

```bash
npm install mongoose —save
```

<div dir="rtl">
استفاده از پکیج : 
</div>

```javascript
const mongoose = require(‘mongoose’);
```

<div dir="rtl">
تنظیمات اولیه :
</div>

```javascript
mongoose.Promise = global.Promise;
mongoose.connect('mongodb://localhost/DATABASENAME');
```