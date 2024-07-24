***

# AccountingEntryInvoicePosition

Class AccountingEntryInvoicePosition



* Full name: `\PlanetaDelEste\GW\Models\AccountingEntryInvoicePosition`
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

### appends



```php
protected $appends
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

### morphTo



```php
public array $morphTo
```






***

## Methods


### getDebitAttribute



```php
public getDebitAttribute(mixed $fValue): float
```








**Parameters:**

| Parameter | Type | Description |
|-----------|------|-------------|
| `$fValue` | **mixed** |  |





***

### getCreditAttribute



```php
public getCreditAttribute(mixed $fValue): float
```








**Parameters:**

| Parameter | Type | Description |
|-----------|------|-------------|
| `$fValue` | **mixed** |  |





***

### getCodeExistsAttribute



```php
public getCodeExistsAttribute(): bool
```












***

### getValidAttribute



```php
public getValidAttribute(): bool
```












***

### getErrorsAttribute



```php
public getErrorsAttribute(): array
```












***


***
> Automatically generated on 2024-05-24
