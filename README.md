# subsette

A dash-boarding environment for datasette.

```
ls templates/pages/dashboard/page2.html | entr datasette bigmac.db --template-dir templates --static static:static
# dashboard will be live at
# http://127.0.0.1:8001/dashboard/page2
```