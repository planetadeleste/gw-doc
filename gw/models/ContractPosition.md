***

# ContractPosition

Class ContractPosition



* Full name: `\PlanetaDelEste\GW\Models\ContractPosition`
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

### belongsToMany



```php
public array $belongsToMany
```






***

## Methods


### scopeGetByContract



```php
public scopeGetByContract(\October\Rain\Database\Builder|self $obQuery, mixed $id): \October\Rain\Database\Builder|self
```








**Parameters:**

| Parameter | Type | Description |
|-----------|------|-------------|
| `$obQuery` | **\October\Rain\Database\Builder&#124;self** |  |
| `$id` | **mixed** |  |





***

### getPriceWithoutTaxAttribute



```php
public getPriceWithoutTaxAttribute(): mixed
```












***

### getNextDateAttribute



```php
public getNextDateAttribute(): mixed
```












***

### getLastDateAttribute



```php
public getLastDateAttribute(): mixed
```












***

### getCanCreateInvoiceAttribute



```php
public getCanCreateInvoiceAttribute(): bool
```












***

### getInvoiceTypeAttribute



```php
public getInvoiceTypeAttribute(): \PlanetaDelEste\GW\Models\InvoiceType|null
```












***

### nextDate



```php
protected nextDate(\Carbon\Carbon $obStartDate, mixed $next = true): ?\Carbon\CarbonInterface
```








**Parameters:**

| Parameter | Type | Description |
|-----------|------|-------------|
| `$obStartDate` | **\Carbon\Carbon** |  |
| `$next` | **mixed** |  |





***


***
> Automatically generated on 2024-05-24
