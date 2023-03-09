Original Question: https://serverfault.com/q/1124059/102173

**Warning**: Please do not use it in a production server.

To test

- Backup your existing nginx.conf and then copy nginx.conf from here to your server.
- Restart Nginx (ex: on Debian / Ubuntu... `nginx -t && systemctl restart nginx`)
- Point any domain to your server.
- Create the dir `/var/www/html`
- run `echo 'Home page' > /var/www/html/index.html`
- run `mkdir -p /var/www/html/view`
- run `echo 'Test page' > /var/www/html/views/test.html`
- Run curl for the following URLs...

```
/
# output should be 'Home page'
/test
# output should be 'Test page'
```

