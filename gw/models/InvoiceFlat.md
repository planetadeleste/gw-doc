***

# InvoiceFlat

Class InvoiceFlat.



* Full name: `\PlanetaDelEste\GW\Models\InvoiceFlat`
* Parent class: [`Model`](../../../Model.md)
* This class implements:
[`\Astrotomic\CachableAttributes\CachableAttributes`](../../../Astrotomic/CachableAttributes/CachableAttributes.md)



## Properties


### table



```php
public string $table
```






***

### rules



```php
public array $rules
```






***

### jsonable



```php
public array $jsonable
```






***

### casts



```php
protected $casts
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

### cachableAttributes



```php
public $cachableAttributes
```






***

### cacheFor



```php
public $cacheFor
```






***

### cachePrefix



```php
public $cachePrefix
```






***

### cacheDriver



```php
public $cacheDriver
```






***

### dates



```php
public array $dates
```






***

### belongsTo



```php
public array $belongsTo
```






***

## Methods


### getTotalPriceValueAttribute



```php
public getTotalPriceValueAttribute(): float
```












***

### getRateAttribute



```php
public getRateAttribute(mixed $sValue = null): mixed
```








**Parameters:**

| Parameter | Type | Description |
|-----------|------|-------------|
| `$sValue` | **mixed** |  |





***

### getUcfeObjectAttribute



```php
public getUcfeObjectAttribute(): mixed
```












***

### getCfeCodeAttribute



```php
public getCfeCodeAttribute(): ?string
```












***

### getItemsAttribute



```php
public getItemsAttribute(): mixed
```












***

### getPositionTotalPriceValueAttribute

Get positions price with all discounts applied.

```php
public getPositionTotalPriceValueAttribute(): int|mixed
```












***

### getPositionTotalValueAttribute

Get positions price with inline discounts applied.

```php
public getPositionTotalValueAttribute(): mixed
```












***

### getTotalPriceWithoutTaxValueAttribute



```php
public getTotalPriceWithoutTaxValueAttribute(): float
```












***

### getTotalDiscountsAttribute



```php
public getTotalDiscountsAttribute(): mixed
```












***

### getTotalTaxValueAttribute



```php
public getTotalTaxValueAttribute(): mixed
```












***

### getRoundedPriceValueAttribute



```php
public getRoundedPriceValueAttribute(): float
```












***

### getTaxValueListAttribute



```php
public getTaxValueListAttribute(): mixed
```












***

### getTaxValueList



```php
public getTaxValueList(\Closure $fnConvert = null, string $sTaxCode = null): array
```








**Parameters:**

| Parameter | Type | Description |
|-----------|------|-------------|
| `$fnConvert` | **\Closure** |  |
| `$sTaxCode` | **string** |  |





***

### getFlatTaxes



```php
public getFlatTaxes(string $sPrefix = &#039;&#039;, bool $invert = false): array
```








**Parameters:**

| Parameter | Type | Description |
|-----------|------|-------------|
| `$sPrefix` | **string** |  |
| `$invert` | **bool** |  |





***

### getIsEresgAttribute



```php
public getIsEresgAttribute(): bool
```












***

### getIsEtckAttribute



```php
public getIsEtckAttribute(): bool
```












***

### getIsEfactAttribute



```php
public getIsEfactAttribute(): bool
```












***

### getIsEremAttribute



```php
public getIsEremAttribute(): bool
```












***

### getIsEboletaAttribute



```php
public getIsEboletaAttribute(): bool
```












***

### scopeGetByInvoice



```php
public scopeGetByInvoice(\October\Rain\Database\Builder|self $obQuery, string|int $id): \October\Rain\Database\Builder|self
```








**Parameters:**

| Parameter | Type | Description |
|-----------|------|-------------|
| `$obQuery` | **\October\Rain\Database\Builder&#124;self** |  |
| `$id` | **string&#124;int** |  |





***


***
> Automatically generated on 2024-05-24
