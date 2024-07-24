***

# Account

Class Account



* Full name: `\PlanetaDelEste\GW\Models\Account`
* Parent class: [`Model`](../../../Model.md)



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

### translatable



```php
public array $translatable
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
public array $belongsTo
```






***

### jsonable



```php
protected $jsonable
```






***

## Methods


### getEditableAttribute



```php
public getEditableAttribute(): bool
```











**Throws:**

- [`JWTException`](../../../Tymon/JWTAuth/Exceptions/JWTException.md)



***

### scopeGetByCode



```php
public scopeGetByCode(\October\Rain\Database\Builder|self $obQuery, string $sValue): \October\Rain\Database\Builder|self
```








**Parameters:**

| Parameter | Type | Description |
|-----------|------|-------------|
| `$obQuery` | **\October\Rain\Database\Builder&#124;self** |  |
| `$sValue` | **string** |  |





***

### scopeGetByPaymentMethodCode



```php
public scopeGetByPaymentMethodCode(\October\Rain\Database\Builder|self $obQuery, string $sValue): \October\Rain\Database\Builder|self
```








**Parameters:**

| Parameter | Type | Description |
|-----------|------|-------------|
| `$obQuery` | **\October\Rain\Database\Builder&#124;self** |  |
| `$sValue` | **string** |  |





***


***
> Automatically generated on 2024-05-24
