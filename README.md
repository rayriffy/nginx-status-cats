# HTTP Status Cats for NGINX

## Setup

Clone this repo to `/etc/nginx/snippets`.
Insert the following snippet into the server block that is going to use the new error pages:

```nginx
include /etc/nginx/snippets/nginx-status-cats/error-cat.conf;
```

Done!
