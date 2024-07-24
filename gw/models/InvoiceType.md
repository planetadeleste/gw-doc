***

# InvoiceType

Class InvoiceType



* Full name: `\PlanetaDelEste\GW\Models\InvoiceType`
* Parent class: [`Model`](../../../Model.md)


## Constants

| Constant | Visibility | Type | Value |
|:---------|:-----------|:-----|:------|
|`ETICKET`|public|int|101|
|`NC_ETICKET`|public|int|102|
|`ND_ETICKET`|public|int|103|
|`CA_ETICKET`|public|int|131|
|`NC_CA_ETICKET`|public|int|132|
|`ND_CA_ETICKET`|public|int|133|
|`EFACTURA`|public|int|111|
|`NC_EFACTURA`|public|int|112|
|`ND_EFACTURA`|public|int|113|
|`EXP_EFACTURA`|public|int|121|
|`NC_EXP_EFACTURA`|public|int|122|
|`ND_EXP_EFACTURA`|public|int|123|
|`CA_EFACTURA`|public|int|141|
|`NC_CA_EFACTURA`|public|int|142|
|`ND_CA_EFACTURA`|public|int|143|
|`EBOLETA`|public|int|151|
|`NC_EBOLETA`|public|int|152|
|`ND_EBOLETA`|public|int|153|
|`EREMITO`|public|int|181|
|`EXP_EREMITO`|public|int|124|
|`ERESGUARDO`|public|int|182|
|`ERECIBO`|public|int|701|
|`ECOBRANZA`|public|int|901|

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

### dates



```php
public array $dates
```






***

### hasMany



```php
public $hasMany
```






***

### belongsToMany



```php
public $belongsToMany
```






***

## Methods


### getShortNameAttribute



```php
public getShortNameAttribute(string $sValue = null): ?string
```








**Parameters:**

| Parameter | Type | Description |
|-----------|------|-------------|
| `$sValue` | **string** |  |





***

### getCodeValueAttribute



```php
public getCodeValueAttribute(): int
```












***

### scopeGetByDgi



```php
public scopeGetByDgi(\October\Rain\Database\Builder|self $obQuery): \October\Rain\Database\Builder|self
```








**Parameters:**

| Parameter | Type | Description |
|-----------|------|-------------|
| `$obQuery` | **\October\Rain\Database\Builder&#124;self** |  |





***

### getUcfeShortNameOptions



```php
public static getUcfeShortNameOptions(): array
```



* This method is **static**.








***


***
> Automatically generated on 2024-05-24
