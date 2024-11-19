# nextcld
nextcloud testing

if NEXTCLOUD_TRUSTED_DOMAINS doesnt work, setup at `config.php`:
```php
'trusted_domains' => 
  array (
    0 => 'localhost',
  ),
```