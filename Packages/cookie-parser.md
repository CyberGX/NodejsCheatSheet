
<div dir="rtl">
نصب پکیج : 
</div>

```bash
npm install cookie-parser —save
```

<div dir="rtl">
استفاده از پکیج : 
</div>

```javascript
const cookieParser = require(‘cookie-parser’);
```

<div dir="rtl">
تنظیمات اولیه :
</div>

```javascript
app.use(cookieParser(‘MYSECRETKEY’));
```