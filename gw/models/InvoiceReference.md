***

# InvoiceReference

Class InvoiceReference.



* Full name: `\PlanetaDelEste\GW\Models\InvoiceReference`
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

## Methods


### scopeGetByInvoice



```php
public scopeGetByInvoice(\October\Rain\Database\Builder|self $obQuery, int|int[] $arInvoiceId): \October\Rain\Database\Builder|self
```








**Parameters:**

| Parameter | Type | Description |
|-----------|------|-------------|
| `$obQuery` | **\October\Rain\Database\Builder&#124;self** |  |
| `$arInvoiceId` | **int&#124;int[]** |  |





***

### scopeGetByInvoiceRef



```php
public scopeGetByInvoiceRef(\October\Rain\Database\Builder|self $obQuery, int|int[] $arInvoiceId): \October\Rain\Database\Builder|self
```








**Parameters:**

| Parameter | Type | Description |
|-----------|------|-------------|
| `$obQuery` | **\October\Rain\Database\Builder&#124;self** |  |
| `$arInvoiceId` | **int&#124;int[]** |  |





***

### beforeCreate



```php
protected beforeCreate(): mixed
```












***


***
> Automatically generated on 2024-05-24
