***

# CompanyMovementType

Class CompanyMovementType



* Full name: `\PlanetaDelEste\GW\Models\CompanyMovementType`
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


### scopeGetByInvoiceMovementType



```php
public scopeGetByInvoiceMovementType(\October\Rain\Database\Builder|self $obQuery, int|string $id, mixed $isCash = true): \October\Rain\Database\Builder|self
```








**Parameters:**

| Parameter | Type | Description |
|-----------|------|-------------|
| `$obQuery` | **\October\Rain\Database\Builder&#124;self** |  |
| `$id` | **int&#124;string** |  |
| `$isCash` | **mixed** |  |





***

### scopeGetByInvoiceMovementTypeCode



```php
public scopeGetByInvoiceMovementTypeCode(\October\Rain\Database\Builder|self $obQuery, string $sCode): \October\Rain\Database\Builder|self
```








**Parameters:**

| Parameter | Type | Description |
|-----------|------|-------------|
| `$obQuery` | **\October\Rain\Database\Builder&#124;self** |  |
| `$sCode` | **string** |  |





***


***
> Automatically generated on 2024-05-24
