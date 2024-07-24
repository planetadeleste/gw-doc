***

# AccountConfig

Class AccountConfig



* Full name: `\PlanetaDelEste\GW\Models\AccountConfig`
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

### jsonable



```php
protected $jsonable
```






***

### belongsTo



```php
public array $belongsTo
```






***

### casts



```php
protected $casts
```






***

## Methods


### scopeGetByPaymentMethod



```php
public scopeGetByPaymentMethod(\October\Rain\Database\Builder|self $obQuery, mixed $id): \October\Rain\Database\Builder|self
```








**Parameters:**

| Parameter | Type | Description |
|-----------|------|-------------|
| `$obQuery` | **\October\Rain\Database\Builder&#124;self** |  |
| `$id` | **mixed** |  |





***

### scopeGetByCurrency



```php
public scopeGetByCurrency(\October\Rain\Database\Builder|self $obQuery, int|string $iCurrencyId): \October\Rain\Database\Builder|self
```








**Parameters:**

| Parameter | Type | Description |
|-----------|------|-------------|
| `$obQuery` | **\October\Rain\Database\Builder&#124;self** |  |
| `$iCurrencyId` | **int&#124;string** |  |





***

### scopeGetByAnyCurrency



```php
public scopeGetByAnyCurrency(\October\Rain\Database\Builder|self $obQuery): \October\Rain\Database\Builder|self
```








**Parameters:**

| Parameter | Type | Description |
|-----------|------|-------------|
| `$obQuery` | **\October\Rain\Database\Builder&#124;self** |  |





***


***
> Automatically generated on 2024-05-24
