# Cálculo de Frete
Classe PHP para cálculo de prazo e valor nos correios.

Exemplo:

```php
$frete = new Frete(
    $cepDeOrigem, 
    $cepDeDestino, 
    $peso, 
    $comprimento, 
    $altura, 
    $largura, 
    $valor
);

echo $frete->getValor();//Obtem o valor do frete

echo $frete->getPrazoEntrega();//Obtem o prazo de entrega em dias

echo $frete->getObs();//Obtem observações sobre o frete
```

License
----

MIT License - http://www.opensource.org/licenses/mit-license.php