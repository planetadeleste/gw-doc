***

# Branch

Class Branch.



* Full name: `\PlanetaDelEste\GW\Models\Branch`
* Parent class: [`Model`](../../../Model.md)
* This class implements:
[`\OwenIt\Auditing\Contracts\Auditable`](../../../OwenIt/Auditing/Contracts/Auditable.md)



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

### slugs



```php
public array $slugs
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

### belongsToMany



```php
public $belongsToMany
```






***

### morphOne



```php
public $morphOne
```






***

## Methods


### scopeDefaults



```php
public scopeDefaults(\October\Rain\Database\Builder|static $obQuery): \October\Rain\Database\Builder|static
```








**Parameters:**

| Parameter | Type | Description |
|-----------|------|-------------|
| `$obQuery` | **\October\Rain\Database\Builder&#124;static** |  |





***

### scopeSecondary



```php
public scopeSecondary(\October\Rain\Database\Builder|static $obQuery): \October\Rain\Database\Builder|static
```








**Parameters:**

| Parameter | Type | Description |
|-----------|------|-------------|
| `$obQuery` | **\October\Rain\Database\Builder&#124;static** |  |





***

### scopeGetByProduct



```php
public scopeGetByProduct(\October\Rain\Database\Builder|static $obQuery, int|string $iProductId): \October\Rain\Database\Builder|static
```








**Parameters:**

| Parameter | Type | Description |
|-----------|------|-------------|
| `$obQuery` | **\October\Rain\Database\Builder&#124;static** |  |
| `$iProductId` | **int&#124;string** |  |





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


***
> Automatically generated on 2024-05-24
