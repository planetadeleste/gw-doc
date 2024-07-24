***

# InvoicePosition

Class InvoicePosition



* Full name: `\PlanetaDelEste\GW\Models\InvoicePosition`
* Parent class: [`Model`](../../../Model.md)
* This class implements:
[`\Astrotomic\CachableAttributes\CachableAttributes`](../../../Astrotomic/CachableAttributes/CachableAttributes.md)



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

### cachableAttributes



```php
public $cachableAttributes
```






***

### dates



```php
public array $dates
```






***

### arPriceField



```php
public $arPriceField
```






***

### hasMany



```php
public $hasMany
```






***

### belongsTo



```php
public array $belongsTo
```






***

### belongsToMany



```php
public $belongsToMany
```






***

### morphMany



```php
public $morphMany
```






***

### morphTo



```php
public $morphTo
```






***

## Methods


### scopeGetByInvoice



```php
public scopeGetByInvoice(\October\Rain\Database\Builder|self $obQuery, int|int[] $arInvoiceId): \October\Rain\Database\Builder|\October\Rain\Database\QueryBuilder|\PlanetaDelEste\GW\Models\InvoicePosition
```








**Parameters:**

| Parameter | Type | Description |
|-----------|------|-------------|
| `$obQuery` | **\October\Rain\Database\Builder&#124;self** |  |
| `$arInvoiceId` | **int&#124;int[]** |  |





***

### getUnitPriceAttribute



```php
public getUnitPriceAttribute(): float
```












***

### getUnitPriceWithoutTaxAttribute



```php
public getUnitPriceWithoutTaxAttribute(): float
```












***

### setPriceAttribute



```php
public setPriceAttribute(mixed $sValue): mixed
```








**Parameters:**

| Parameter | Type | Description |
|-----------|------|-------------|
| `$sValue` | **mixed** |  |





***

### getPriceAttribute



```php
public getPriceAttribute(mixed $sValue): float
```








**Parameters:**

| Parameter | Type | Description |
|-----------|------|-------------|
| `$sValue` | **mixed** |  |





***

### getPriceValueAttribute



```php
public getPriceValueAttribute(): float
```












***

### getPriceWithoutTaxAttribute



```php
public getPriceWithoutTaxAttribute(): mixed
```












***

### getPriceWithDiscountsAttribute



```php
public getPriceWithDiscountsAttribute(): float
```












***

### getPriceWithGlobalDiscountsAttribute



```php
public getPriceWithGlobalDiscountsAttribute(): mixed
```












***

### getTaxPercentAttribute



```php
public getTaxPercentAttribute(mixed $sValue = null): mixed
```








**Parameters:**

| Parameter | Type | Description |
|-----------|------|-------------|
| `$sValue` | **mixed** |  |





***

### getTotalWithoutTaxAttribute



```php
public getTotalWithoutTaxAttribute(): mixed
```












***

### getTotalWithoutTaxWithGlobalDiscountsAttribute



```php
public getTotalWithoutTaxWithGlobalDiscountsAttribute(): mixed
```












***

### getTotalWithTaxWithGlobalDiscountsAttribute



```php
public getTotalWithTaxWithGlobalDiscountsAttribute(): float
```











**Throws:**

- [`JWTException`](../../../Tymon/JWTAuth/Exceptions/JWTException.md)



***

### getTotalWithTaxAttribute



```php
public getTotalWithTaxAttribute(): float
```











**Throws:**

- [`JWTException`](../../../Tymon/JWTAuth/Exceptions/JWTException.md)



***

### getTotalTaxAttribute



```php
public getTotalTaxAttribute(): mixed
```











**Throws:**

- [`JWTException`](../../../Tymon/JWTAuth/Exceptions/JWTException.md)



***

### getTotalTaxWithGlobalDiscountsAttribute



```php
public getTotalTaxWithGlobalDiscountsAttribute(): mixed
```











**Throws:**

- [`JWTException`](../../../Tymon/JWTAuth/Exceptions/JWTException.md)



***

### getQuantityBalanceAttribute



```php
public getQuantityBalanceAttribute(): mixed
```












***

### getQuantity



```php
public getQuantity(mixed& $fQuantity = null): int
```








**Parameters:**

| Parameter | Type | Description |
|-----------|------|-------------|
| `$fQuantity` | **mixed** |  |





***

### getPriceBalanceAttribute



```php
public getPriceBalanceAttribute(): mixed
```












***

### getPriceBalance



```php
public getPriceBalance(float& $fPrice): float
```








**Parameters:**

| Parameter | Type | Description |
|-----------|------|-------------|
| `$fPrice` | **float** |  |




**Throws:**

- [`Exception`](../../../Exception.md)



***

### getInvoiceTypeCode



```php
public getInvoiceTypeCode(): int
```












***

### getProduct



```php
public getProduct(): \Lovata\Shopaholic\Models\Product|null
```












***

### currencyRound

Round value by company currency settings

```php
public currencyRound(float $fAmount): float|int|string
```








**Parameters:**

| Parameter | Type | Description |
|-----------|------|-------------|
| `$fAmount` | **float** |  |




**Throws:**

- [`JWTException`](../../../Tymon/JWTAuth/Exceptions/JWTException.md)



***


***
> Automatically generated on 2024-05-24
