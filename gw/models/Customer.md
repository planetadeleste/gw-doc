***

# Customer

Class Customer.



* Full name: `\PlanetaDelEste\GW\Models\Customer`
* Parent class: [`Model`](../../../Model.md)
* This class implements:
[`\OwenIt\Auditing\Contracts\Auditable`](../../../OwenIt/Auditing/Contracts/Auditable.md)


## Constants

| Constant | Visibility | Type | Value |
|:---------|:-----------|:-----|:------|
|`TYPE_CUSTOMER`|public| |1|
|`TYPE_PROVIDER`|public| |2|
|`TYPE_BOTH`|public| |3|

## Properties


### table



```php
public string $table
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

### hasOne



```php
public $hasOne
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

### attachOne



```php
public array $attachOne
```






***

## Methods


### getIsCustomerAttribute



```php
public getIsCustomerAttribute(): bool
```












***

### getIsProviderAttribute



```php
public getIsProviderAttribute(): bool
```












***

### scopeGetByProvider



```php
public scopeGetByProvider(\October\Rain\Database\Builder|self $obQuery): \October\Rain\Database\Builder|self
```








**Parameters:**

| Parameter | Type | Description |
|-----------|------|-------------|
| `$obQuery` | **\October\Rain\Database\Builder&#124;self** |  |





***

### scopeGetByCustomer



```php
public scopeGetByCustomer(\October\Rain\Database\Builder|self $obQuery): \October\Rain\Database\Builder|self
```








**Parameters:**

| Parameter | Type | Description |
|-----------|------|-------------|
| `$obQuery` | **\October\Rain\Database\Builder&#124;self** |  |





***

### scopeGetByCode



```php
public scopeGetByCode(\October\Rain\Database\Builder|self $obQuery, mixed $sValue): \October\Rain\Database\Builder|self
```








**Parameters:**

| Parameter | Type | Description |
|-----------|------|-------------|
| `$obQuery` | **\October\Rain\Database\Builder&#124;self** |  |
| `$sValue` | **mixed** |  |





***

### scopeGetByDocId



```php
public scopeGetByDocId(\October\Rain\Database\Builder|self $obQuery, mixed $sValue): \October\Rain\Database\Builder|self
```








**Parameters:**

| Parameter | Type | Description |
|-----------|------|-------------|
| `$obQuery` | **\October\Rain\Database\Builder&#124;self** |  |
| `$sValue` | **mixed** |  |





***

### scopeGetByForeign



```php
public scopeGetByForeign(\October\Rain\Database\Builder|self $obQuery): \October\Rain\Database\Builder|self
```








**Parameters:**

| Parameter | Type | Description |
|-----------|------|-------------|
| `$obQuery` | **\October\Rain\Database\Builder&#124;self** |  |





***

### scopeGetByLocal



```php
public scopeGetByLocal(\October\Rain\Database\Builder|self $obQuery): \October\Rain\Database\Builder|self
```








**Parameters:**

| Parameter | Type | Description |
|-----------|------|-------------|
| `$obQuery` | **\October\Rain\Database\Builder&#124;self** |  |





***

### getFieldList



```php
public getFieldList(): array
```












***


***
> Automatically generated on 2024-05-24
