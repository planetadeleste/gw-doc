***

# AccountingEntryPosition

Class AccountingEntryPosition



* Full name: `\PlanetaDelEste\GW\Models\AccountingEntryPosition`
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

### belongsTo



```php
public array $belongsTo
```






***

### hasMany



```php
public $hasMany
```






***

### morphTo



```php
public $morphTo
```






***

## Methods


### getIsAccountTypeAttribute



```php
public getIsAccountTypeAttribute(): bool
```












***

### getIsPaymentMethodAttribute



```php
public getIsPaymentMethodAttribute(): bool
```












***

### getIterateAttribute



```php
public getIterateAttribute(): bool
```












***

### getIterateTaxAttribute



```php
public getIterateTaxAttribute(): bool
```












***

### getIterateProductAttribute



```php
public getIterateProductAttribute(): bool
```












***

### getIterateCategoryAttribute



```php
public getIterateCategoryAttribute(): bool
```












***

### hasOptions



```php
protected hasOptions(array $arOptions = [&#039;category&#039;, &#039;product&#039;, &#039;tax&#039;, &#039;paymentmethod&#039;]): bool
```








**Parameters:**

| Parameter | Type | Description |
|-----------|------|-------------|
| `$arOptions` | **array** |  |





***

### scopeGetByAccountingEntry



```php
public scopeGetByAccountingEntry(\October\Rain\Database\Builder|self $obQuery, int|int[] $sValue): \October\Rain\Database\Builder|self
```








**Parameters:**

| Parameter | Type | Description |
|-----------|------|-------------|
| `$obQuery` | **\October\Rain\Database\Builder&#124;self** |  |
| `$sValue` | **int&#124;int[]** |  |





***


***
> Automatically generated on 2024-05-24
