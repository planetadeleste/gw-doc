***

# AccountingMovementType

Class AccountingMovementType



* Full name: `\PlanetaDelEste\GW\Models\AccountingMovementType`
* Parent class: [`Model`](../../../Model.md)


## Constants

| Constant | Visibility | Type | Value |
|:---------|:-----------|:-----|:------|
|`CODE_SELL_CASH`|public| |&#039;VENTA_CONTADO&#039;|
|`CODE_SELL_CREDIT`|public| |&#039;VENTA_CREDITO&#039;|
|`CODE_PURCHASE_CASH`|public| |&#039;COMPRA_CONTADO&#039;|
|`CODE_PURCHASE_CREDIT`|public| |&#039;COMPRA_CREDITO&#039;|
|`CODE_REFOUND_CASH`|public| |&#039;DEVOLUCION_CONTADO&#039;|
|`CODE_REFOUND_CREDIT`|public| |&#039;DEVOLUCION_CREDITO&#039;|
|`CODE_REFOUND_PURCHASE_CASH`|public| |&#039;DEVOLUCION_COMPRA_CONTADO&#039;|
|`CODE_REFOUND_PURCHASE_CREDIT`|public| |&#039;DEVOLUCION_COMPRA_CREDITO&#039;|
|`CODE_DEBIT_NOTE_CASH`|public| |&#039;NOTA_DEBITO_CONTADO&#039;|
|`CODE_DEBIT_NOTE_CREDIT`|public| |&#039;NOTA_DEBITO_CREDITO&#039;|
|`CODE_RECEIPT`|public| |&#039;RESGUARDO&#039;|
|`CODE_RECEIPT_CORRECT`|public| |&#039;CORRECCION_RESGUARDO&#039;|
|`CODE_DEBT`|public| |&#039;RECIBO_COBRANZA&#039;|

## Properties


### table



```php
public string $table
```






***

### attributeNames



```php
public array $attributeNames
```






***

### rules



```php
public array $rules
```






***

### fillable



```php
public array $fillable
```






***

### cached



```php
public array $cached
```






***

### dates



```php
public array $dates
```






***

### belongsTo



```php
public $belongsTo
```






***

### hasMany



```php
public array $hasMany
```






***

## Methods


### getUseCashCreditAttribute



```php
public getUseCashCreditAttribute(): bool
```












***

### scopeGetByInvoiceMovementType



```php
public scopeGetByInvoiceMovementType(\October\Rain\Database\Builder|self $obQuery, int|int[] $sValue): \October\Rain\Database\Builder|self
```








**Parameters:**

| Parameter | Type | Description |
|-----------|------|-------------|
| `$obQuery` | **\October\Rain\Database\Builder&#124;self** |  |
| `$sValue` | **int&#124;int[]** |  |





***


***
> Automatically generated on 2024-05-24
