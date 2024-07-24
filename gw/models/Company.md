***

# Company

Class Company.



* Full name: `\PlanetaDelEste\GW\Models\Company`
* Parent class: [`Model`](../../../Model.md)
* This class implements:
[`\OwenIt\Auditing\Contracts\Auditable`](../../../OwenIt/Auditing/Contracts/Auditable.md), [`\Astrotomic\CachableAttributes\CachableAttributes`](../../../Astrotomic/CachableAttributes/CachableAttributes.md)



## Properties


### table



```php
public string $table
```






***

### implement



```php
public array $implement
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

### cachableAttributes



```php
public $cachableAttributes
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

### hasOne



```php
public $hasOne
```






***

### hasMany



```php
public array $hasMany
```






***

### belongsToMany



```php
public array $belongsToMany
```






***

### morphOne



```php
public $morphOne
```






***

### attachOne



```php
public array $attachOne
```






***

## Methods


### scopeGetByUser



```php
public scopeGetByUser(\October\Rain\Database\Builder|static $obQuery, int|string $iUserId): \October\Rain\Database\Builder|static
```








**Parameters:**

| Parameter | Type | Description |
|-----------|------|-------------|
| `$obQuery` | **\October\Rain\Database\Builder&#124;static** |  |
| `$iUserId` | **int&#124;string** |  |





***

### scopeGetByCategory



```php
public scopeGetByCategory(\October\Rain\Database\Builder|static $obQuery, int|string $iCategoryId): \October\Rain\Database\Builder|static
```








**Parameters:**

| Parameter | Type | Description |
|-----------|------|-------------|
| `$obQuery` | **\October\Rain\Database\Builder&#124;static** |  |
| `$iCategoryId` | **int&#124;string** |  |





***

### scopeGetByDocId



```php
public scopeGetByDocId(\October\Rain\Database\Builder|static $obQuery, int|string $sDocId): mixed
```








**Parameters:**

| Parameter | Type | Description |
|-----------|------|-------------|
| `$obQuery` | **\October\Rain\Database\Builder&#124;static** |  |
| `$sDocId` | **int&#124;string** |  |





***

### getDocIdAttribute



```php
public getDocIdAttribute(): ?string
```












***

### getDocTypeAttribute



```php
public getDocTypeAttribute(): ?string
```












***

### getIsEmptyAttribute



```php
public getIsEmptyAttribute(): bool
```












***

### getBalanceAttribute



```php
public getBalanceAttribute(): mixed
```












***

### getUsdBalanceAttribute



```php
public getUsdBalanceAttribute(): mixed
```












***

### getUnsignedBalanceAttribute



```php
public getUnsignedBalanceAttribute(): mixed
```












***

### getUsdUnsignedBalanceAttribute



```php
public getUsdUnsignedBalanceAttribute(): mixed
```












***

### getBalance



```php
protected getBalance(string $sCurrency = MoneyHelper::CURRENCY_BASE, bool $signed = true): mixed
```








**Parameters:**

| Parameter | Type | Description |
|-----------|------|-------------|
| `$sCurrency` | **string** |  |
| `$signed` | **bool** |  |





***


***
> Automatically generated on 2024-05-24
