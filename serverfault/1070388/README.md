Original Question: https://serverfault.com/q/1070388/102173

**Warning**: Please do not use it in a production server.

To test, backup your existing nginx.conf and then copy nginx.conf from here to your server.

Run `nginx -t && systemctl restart nginx`

Point any domain to your server.

Run curl for the following URLs...

```
xyz/asset.html
abc/test.html
xyz/abc/test.html
xyz/abc/qwerty/test2.html
```

A temporary test site is available at 1070388.tinywp.dev for now!
