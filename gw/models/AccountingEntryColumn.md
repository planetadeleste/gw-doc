***

# AccountingEntryColumn

Class AccountingEntryColumn



* Full name: `\PlanetaDelEste\GW\Models\AccountingEntryColumn`
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


### getItemAttribute



```php
public getItemAttribute(): ?\Model
```












***

### getValueAttribute



```php
public getValueAttribute(): mixed
```












***

### getNameAttribute



```php
public getNameAttribute(string $sValue = null): mixed
```








**Parameters:**

| Parameter | Type | Description |
|-----------|------|-------------|
| `$sValue` | **string** |  |





***

### scopeGetByPosition



```php
public scopeGetByPosition(\October\Rain\Database\Builder|self $obQuery, int|int[] $sValue): \October\Rain\Database\Builder|self
```








**Parameters:**

| Parameter | Type | Description |
|-----------|------|-------------|
| `$obQuery` | **\October\Rain\Database\Builder&#124;self** |  |
| `$sValue` | **int&#124;int[]** |  |





***


***
> Automatically generated on 2024-05-24
