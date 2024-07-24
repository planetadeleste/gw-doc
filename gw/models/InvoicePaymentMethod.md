***

# InvoicePaymentMethod

Class InvoicePaymentMethod



* Full name: `\PlanetaDelEste\GW\Models\InvoicePaymentMethod`
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

### jsonable



```php
protected $jsonable
```






***

## Methods


### getCompanyIdAttribute



```php
public getCompanyIdAttribute(): ?int
```












***

### scopeGetByInvoice



```php
public scopeGetByInvoice(\October\Rain\Database\Builder|self $obQuery, int|int[] $arInvoiceId): \October\Rain\Database\Builder|\October\Rain\Database\QueryBuilder
```








**Parameters:**

| Parameter | Type | Description |
|-----------|------|-------------|
| `$obQuery` | **\October\Rain\Database\Builder&#124;self** |  |
| `$arInvoiceId` | **int&#124;int[]** |  |





***

### scopeGetByPaymentMethod



```php
public scopeGetByPaymentMethod(\October\Rain\Database\Builder|self $obQuery, int|int[] $arValueId): \October\Rain\Database\Builder|\October\Rain\Database\QueryBuilder
```








**Parameters:**

| Parameter | Type | Description |
|-----------|------|-------------|
| `$obQuery` | **\October\Rain\Database\Builder&#124;self** |  |
| `$arValueId` | **int&#124;int[]** |  |





***

### beforeSave



```php
protected beforeSave(): mixed
```












***


***
> Automatically generated on 2024-05-24
