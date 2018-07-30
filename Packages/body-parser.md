<div dir="rtl">
توضیحات : 
<br><br>
کتابخانه Body-Parser جهت دسترسی به محتوایت Body درخواست های وب می باشد.
</div>

<div dir="rtl">
<br>
نصب پکیج : 
</div>

```bash
npm install body-parser —save
```

<div dir="rtl">
استفاده از پکیج : 
</div>

```javascript
const bodyParser = require(‘body-parser’);
```

<div dir="rtl">
تنظیمات اولیه :
</div>

```javascript
app.use(bodyParser.json());
app.use(bodyParser.urlencoded({ extended : true }));
```