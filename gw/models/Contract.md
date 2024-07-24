***

# Contract

Class Contract



* Full name: `\PlanetaDelEste\GW\Models\Contract`
* Parent class: [`Model`](../../../Model.md)


## Constants

| Constant | Visibility | Type | Value |
|:---------|:-----------|:-----|:------|
|`STATUS_INIT`|public| |&#039;init&#039;|
|`STATUS_ACTIVE`|public| |&#039;active&#039;|
|`STATUS_ENDED`|public| |&#039;ended&#039;|
|`STATUS_OVERDUE`|public| |&#039;overdue&#039;|

## Properties


### table



```php
public string $table
```






***

### with



```php
protected $with
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

### hasMany



```php
public array $hasMany
```






***

### belongsTo



```php
public array $belongsTo
```






***

### morphOne



```php
public array $morphOne
```






***

## Methods


### scopeGetByCustomer



```php
public scopeGetByCustomer(\October\Rain\Database\Builder|self $obQuery, mixed $sCustomerId): \October\Rain\Database\Builder|self
```








**Parameters:**

| Parameter | Type | Description |
|-----------|------|-------------|
| `$obQuery` | **\October\Rain\Database\Builder&#124;self** |  |
| `$sCustomerId` | **mixed** |  |





***

### scopeGetByProduct



```php
public scopeGetByProduct(\October\Rain\Database\Builder|self $obQuery, mixed $sValue): \October\Rain\Database\Builder|self
```








**Parameters:**

| Parameter | Type | Description |
|-----------|------|-------------|
| `$obQuery` | **\October\Rain\Database\Builder&#124;self** |  |
| `$sValue` | **mixed** |  |





***

### getFrequencyAttribute



```php
public getFrequencyAttribute(): ?string
```












***

### getLatestInvoiceAttribute



```php
public getLatestInvoiceAttribute(): ?\PlanetaDelEste\GW\Models\Invoice
```












***

### getStartDateAttribute



```php
public getStartDateAttribute(): ?\October\Rain\Argon\Argon
```












***

### getNextDateAttribute



```php
public getNextDateAttribute(): ?\Carbon\Carbon
```












***

### getLastDateAttribute



```php
public getLastDateAttribute(): ?\Carbon\Carbon
```












***

### getOldestPosition



```php
protected getOldestPosition(): ?\PlanetaDelEste\GW\Models\ContractPosition
```












***

### getStatusAttribute



```php
public getStatusAttribute(): string
```












***

### getCanCreateInvoiceAttribute



```php
public getCanCreateInvoiceAttribute(): bool
```












***


***
> Automatically generated on 2024-05-24
