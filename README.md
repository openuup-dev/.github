# OpenUUP

This is an enhanced fork of UUP dump.

## Deployment

Something like this:

```bash
git clone --recurse-submodules https://codeberg.org/openuup/web.git openuup
php -S localhost:3000 -t openuup
```

### Requirements

- Git
- PHP
- `curl` extension
- `max_execution_time` set to `120`
    - This is optional but you will have many timed out fetches otherwise.