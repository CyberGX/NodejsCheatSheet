<div dir="rtl">
نصب پکیج : 
</div>

```bash
npm install express-session —save
```

<div dir="rtl">
استفاده از پکیج : 
</div>

```javascript
const session = require(‘express-session’);
```

<div dir="rtl">
تنظیمات اولیه :
</div>

```javascript
app.use(session({
  secret : 'MYSECRETKEY',
  resave : true,
  saveUninitialize: true,
  store : new MongoStore({ mongoose.connection }) // if Use MongoDB for Sessions
}));
```