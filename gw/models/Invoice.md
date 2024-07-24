***

# Invoice

Class Invoice.



* Full name: `\PlanetaDelEste\GW\Models\Invoice`
* Parent class: [`Model`](../../../Model.md)
* This class implements:
[`\OwenIt\Auditing\Contracts\Auditable`](../../../OwenIt/Auditing/Contracts/Auditable.md), [`\Astrotomic\CachableAttributes\CachableAttributes`](../../../Astrotomic/CachableAttributes/CachableAttributes.md)

**See Also:**

* \PlanetaDelEste\GW\Traits\Invoice\InvoiceAccessorsTrait - SCOPES
* \PlanetaDelEste\GW\Traits\Invoice\InvoiceScopesTrait - 


## Constants

| Constant | Visibility | Type | Value |
|:---------|:-----------|:-----|:------|
|`EVENT_AFTER_SIGN`|public| |&#039;planetadeleste.gw.invoice.afterSign&#039;|
|`FLAG_SIGNING`|public| |&#039;signing&#039;|
|`FLAG_SIGNED`|public| |&#039;signed&#039;|
|`FLAG_SIGN_ERROR`|public| |&#039;sign_error&#039;|

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

### jsonable



```php
public array $jsonable
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

### hasOne



```php
public array $hasOne
```






***

### attachOne



```php
public $attachOne
```






***

### hasMany



```php
public array $hasMany
```






***

### morphOne



```php
public array $morphOne
```






***

### morphMany



```php
public $morphMany
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

## Methods


### getBalance



```php
public getBalance(bool $bForce = false, bool $rounded = false, ?\Carbon\Carbon $obDate = null): float
```








**Parameters:**

| Parameter | Type | Description |
|-----------|------|-------------|
| `$bForce` | **bool** | Get balance without check skip_balance property |
| `$rounded` | **bool** |  |
| `$obDate` | **?\Carbon\Carbon** |  |




**Throws:**

- [`JWTException`](../../../Tymon/JWTAuth/Exceptions/JWTException.md)



***

### getTaxValueList



```php
public getTaxValueList(?\Closure $fnConvert = null): array
```








**Parameters:**

| Parameter | Type | Description |
|-----------|------|-------------|
| `$fnConvert` | **?\Closure** |  |





***

### hasGlobalReferences



```php
public hasGlobalReferences(): bool
```












***

### updateDgiStatus



```php
public updateDgiStatus(): void
```











**Throws:**

- [`JWTException`](../../../Tymon/JWTAuth/Exceptions/JWTException.md)



***

### calculateDiscounts

Calculate discounts.

```php
protected calculateDiscounts(float& $fValue, bool $calculateOnly = false): float
```








**Parameters:**

| Parameter | Type | Description |
|-----------|------|-------------|
| `$fValue` | **float** |  |
| `$calculateOnly` | **bool** |  |





***


***
> Automatically generated on 2024-05-24
