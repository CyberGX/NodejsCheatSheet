<div dir="rtl">
نصب پکیج : 
</div>

```bash
npm install http —save
```

<div dir="rtl">
استفاده از پکیج : 
</div>

```javascript
const http = require(‘http’);

// Lets define a port we want to listen to
const PORT=3000
 
// We need a function which handles requests and send response
let handleRequest = (req, res) => {
  res.end('It Works - ' + req.url);
}
 
// Create a server
let server = http.createServer(handleRequest);
 
// Lets start our server
server.listen(PORT, () => {
    console.log("Server listening on: http://localhost:%s", PORT);
});
```

<div dir="rtl">
 در صورتی که سرور را برای اکسپرس می خواهیم آماده کنیم :
</div>


```javascript
// if Use Express JS
const server = http.createServer(app)
server.listen(PORT, () => console.log('listening on port %s', PORT));
```