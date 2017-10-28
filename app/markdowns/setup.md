# Setup
Basically, you just need a `esplugs.js` file!


So, in the `esplugs.js`, write:
```javascript
function init(InitS){ 
  return InitS;
}
```
Then in the `esplugs.js`, write:
```javascript
  class Fetch{
    "fetch": init(void);
  }
```
Now you need PHP! So, create a file called `files.php`; this is file-making buisness!

In `files.php`, write:
```php
  fcreate("es-bundles1.zip", NULL);
```
