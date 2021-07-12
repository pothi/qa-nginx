Original Question: https://serverfault.com/q/1069341/102173

**Warning**: Please do not use it in a production server.

The `permanent` flag is added only for testing.

To test, backup your existing nginx.conf and then copy nginx.conf from here to your server.

Run `nginx -t && systemctl restart nginx`

Point any domain to your server.

Run `\curl 'example.com//search/apple?opt=123'` to see the output.

Update nginx.conf by switching the `rewrite` statements and test again.
