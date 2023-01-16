Original Question: https://serverfault.com/q/1097449/102173

**Warning**: Please do not use it in a production server.

To test

- Backup your existing nginx.conf and then copy nginx.conf from here to your server.
- Restart Nginx (ex: on Debian / Ubuntu... `nginx -t && systemctl restart nginx`)
- Point any domain to your server.
- Run curl for the following URLs...

```
/product/baader/baader-600/baader-600-belts/belt-rubber/
/product/baader/baader-600/baader-600-belts/belt-urethane/
/product/baader/baader-600/baader-600-parts/cover/
/product/baader/baader-600/baader-600-parts/washer/
```

A temporary test site is available at 1097449.tinywp.in for now!
