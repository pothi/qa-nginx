Original Question: https://serverfault.com/q/1119920/102173

**Warning**: Please do not use it in a production server.

To test

- Backup your existing nginx.conf and then copy nginx.conf from here to your server.
- Restart Nginx (ex: on Debian / Ubuntu... `nginx -t && systemctl restart nginx`)
- Point any domain to your server.
- Run curl for the following URLs...

```
/some-urltext-nav.html
```

A temporary test site is available at 1119920.tinywp.in for now!
