<div dir="rtl">
توضیحات پکیج : 
<br>
ExpressJS فریمورک وب برای نود جی اس  می باشد که با فراهم کردن بستر توسعه وب بر روی این زبان کار ایجاد یک وب سایت را ساده سازی کرده است.
<br>
* نسخه های جدیدی که برای ExpreeJS ساخته می شود رویکرد Backward Compatibility دارد و کد هایی که در نسخه های پیشین برنامه نویسی شده باشد همچنان پشتیبانی می شود.
<br>

</div>

<div dir="rtl">
نصب پکیج : 
</div>

```bash
npm install express —save
```

<div dir="rtl">
استفاده از پکیج : 
</div>

```javascript
const express = require(‘express’);
const app = express();
```

<div dir="rtl">
Middleware ها :
<br><br>
در اکسپرس جهت تعریف یک Middleware از app.use استفاده می شود.
<br>
Middleware ها جهت اجرا در هر درخواست تعریف میشوند تا برای مثال اعتبار سنجی ورود کاربر را چک کنند.
</div>

<div dir="rtl">
<br><br>
تعریف شاخه فایل های ثابت :
</div>

```javascript
app.use(express.static('public'));
```

<div dir="rtl">
تعریف موتور پردازش قالب :
</div>

```javascript
app.set('view engine', 'ejs');
```

<div dir="rtl">
تعریف شاخه فایل های View :
</div>

```javascript
app.set('views', path.resolve('./resources/views'));
```

<div dir="rtl">
تنظیمات اولیه :
</div>

```javascript
app.use(bodyParser.json());
app.use(bodyParser.urlencoded({ extended : true }));
```