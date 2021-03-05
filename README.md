# valleus-http-error-pages
Just a simple error pages

| Error Pages | Completion |
|-|-|
|404|✅|
|301|✅|
|403|✅|
|500|✅|
|502|✅|
|503|✅|
|504|✅|
|444|✅|

just clone this repo and move the error pages to /usr/share/nginx/html
include the globalerror file in your nginx configs.

To enable the error pages paste the follwing in `server` of your config

```nginx
include globalerror;
```