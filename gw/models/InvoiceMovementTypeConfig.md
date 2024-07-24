***

# InvoiceMovementTypeConfig

Class InvoiceMovementTypeConfig



* Full name: `\PlanetaDelEste\GW\Models\InvoiceMovementTypeConfig`
* Parent class: [`Model`](../../../Model.md)



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

## Methods


### getNameAttribute



```php
public getNameAttribute(): string
```












***

### scopeGetByMovementType



```php
public scopeGetByMovementType(\October\Rain\Database\Builder|self $obQuery, int|int[] $iValue): \October\Rain\Database\Builder|self
```








**Parameters:**

| Parameter | Type | Description |
|-----------|------|-------------|
| `$obQuery` | **\October\Rain\Database\Builder&#124;self** |  |
| `$iValue` | **int&#124;int[]** |  |





***

### scopeGetByMovementTypeCode



```php
public scopeGetByMovementTypeCode(\October\Rain\Database\Builder|self $obQuery, string|string[] $iValue): \October\Rain\Database\Builder|self
```








**Parameters:**

| Parameter | Type | Description |
|-----------|------|-------------|
| `$obQuery` | **\October\Rain\Database\Builder&#124;self** |  |
| `$iValue` | **string&#124;string[]** |  |





***


***
> Automatically generated on 2024-05-24
