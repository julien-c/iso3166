iso3166
=======

ISO 3166-1 alpha-2 mapping:

```php
echo Iso3166\Codes::map('FR');
// 'France'
```

Plus one super handy helper:

```php
echo Iso3166\Codes::select('class', 'name', 'FR');
```

will output:

```html
<select class="class" name="name">
  <option value="AF">Afghanistan</option>
  ...
  <option value="FR" selected>France</option>
  ...
</select>
```
