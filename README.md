# closeallhtmltags
Simple class that closes all opened html tags in a provided string

-- Usage --

```php
<?php

require_once './closeAllHtmlTags.php';

$someMessyHtml = "<p><strong>Bold</p><p>This shoudn't be bold.</p>";
echo '<p>Messy HTML: </p>'.$someMessyHtml.'</strong>';

$cleanHtml  =  closeAllHtmlTags::index($someMessyHtml);
echo '<p>Now it\'s  OK: </p>'.$cleanHtml;
```

