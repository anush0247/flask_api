# setup

```bash
pip install -r requirements.txt
python api_server.py
```

# create_task api

```js
var settings = {
  "async": true,
  "crossDomain": true,
  "url": "http://127.0.0.1:5000/api/tasks/",
  "method": "POST",
  "headers": {
    "content-type": "application/json",
    "cache-control": "no-cache",
    "postman-token": "b475f1dc-60af-8484-d659-101722b13844"
  },
  "processData": false,
  "data": "{\n\t\"test\": \"test\"\n}"
}

$.ajax(settings).done(function (response) {
  console.log(response);
});
```