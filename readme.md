# Logo Métodos de Pagamento

Logo dos principais métodos de pagamento no Brasil em formato `base64`

## Instalação

Faça a instalação no seu projeto via `require`

```sh
$ composer require fernandovaller/payment-methods-logo
```

## Obter o logo do método
```php
<?php

use FVCode\PaymentMethodsLogo\Logo;

require __DIR__ . '/vendor/autoload.php';

echo Logo::get('visa');

/**
 * Out (string):
 * data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAFMAAAA3CAIAAAD ....
 */

echo Logo::getImage('visa', 32);
```

Licença
-
[![License](https://poser.pugx.org/germanoricardi/brazilian-helper/license)](https://packagist.org/packages/germanoricardi/brazilian-helper)
