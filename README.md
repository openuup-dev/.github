# OpenUUP

This is an enhanced fork of UUP dump.

## Deployment

Something like this:

```bash
git clone --recurse-submodules https://codeberg.org/openuup/web.git openuup
php -S localhost:3000 -t openuup
```

Make sure you have PHP and p7zip (or 7-Zip) installed. Also, the `curl` and `zip` extensions are required. It is highly recommended to bump the max execution time in `php.ini` to `120`.