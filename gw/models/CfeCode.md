***

# CfeCode

Class CfeCode



* Full name: `\PlanetaDelEste\GW\Models\CfeCode`
* Parent class: [`Model`](../../../Model.md)



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

## Methods


### scopeGetBySearch



```php
public scopeGetBySearch(\October\Rain\Database\Builder|static $obQuery, string $sValue): \October\Rain\Database\Builder|static
```








**Parameters:**

| Parameter | Type | Description |
|-----------|------|-------------|
| `$obQuery` | **\October\Rain\Database\Builder&#124;static** |  |
| `$sValue` | **string** |  |





***

### scopeGetByCode



```php
public scopeGetByCode(\October\Rain\Database\Builder|self $obQuery, mixed $sCode): \October\Rain\Database\Builder|self
```








**Parameters:**

| Parameter | Type | Description |
|-----------|------|-------------|
| `$obQuery` | **\October\Rain\Database\Builder&#124;self** |  |
| `$sCode` | **mixed** |  |





***

### getCodeAttribute



```php
public getCodeAttribute(): string
```












***


***
> Automatically generated on 2024-05-24
