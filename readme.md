[![Latest Stable Version](http://poser.pugx.org/fernandovaller/flags-brasil-states/v)](https://packagist.org/packages/fernandovaller/flags-brasil-states) [![Total Downloads](http://poser.pugx.org/fernandovaller/flags-brasil-states/downloads)](https://packagist.org/packages/fernandovaller/flags-brasil-states)  [![License](http://poser.pugx.org/fernandovaller/flags-brasil-states/license)](https://packagist.org/packages/fernandovaller/flags-brasil-states)

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

use FVCode\PaymentMethodsLogo\PaymentMethodsLogo;

require __DIR__ . '/vendor/autoload.php';

echo PaymentMethodsLogo::get('visa')

/**
 * Out (string):
 * data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAFMAAAA3CAIAAAD ....
 */
```

Licença
-
[![License](https://poser.pugx.org/germanoricardi/brazilian-helper/license)](https://packagist.org/packages/germanoricardi/brazilian-helper)
