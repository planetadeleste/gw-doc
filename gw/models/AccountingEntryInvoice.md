***

# AccountingEntryInvoice

Class AccountingEntryInvoice



* Full name: `\PlanetaDelEste\GW\Models\AccountingEntryInvoice`
* Parent class: [`Model`](../../../Model.md)


## Constants

| Constant | Visibility | Type | Value |
|:---------|:-----------|:-----|:------|
|`BOOK_SALES`|public| |&#039;V&#039;|
|`BOOK_PURCHASES`|public| |&#039;C&#039;|
|`BOOK_REVENUES`|public| |&#039;I&#039;|
|`BOOK_EXPENSES`|public| |&#039;E&#039;|
|`BOOK_GENERAL_JOURNAL`|public| |&#039;P&#039;|

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

### getBalanceAttribute



```php
public getBalanceAttribute(): float
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

### scopeGetByCurrency



```php
public scopeGetByCurrency(\October\Rain\Database\Builder|self $obQuery, int|string $iCurrencyId): \October\Rain\Database\Builder|self
```








**Parameters:**

| Parameter | Type | Description |
|-----------|------|-------------|
| `$obQuery` | **\October\Rain\Database\Builder&#124;self** |  |
| `$iCurrencyId` | **int&#124;string** |  |





***

### scopeGetByInvoice



```php
public scopeGetByInvoice(\October\Rain\Database\Builder|self $obQuery, int|string $iInvoiceId): \October\Rain\Database\Builder|self
```








**Parameters:**

| Parameter | Type | Description |
|-----------|------|-------------|
| `$obQuery` | **\October\Rain\Database\Builder&#124;self** |  |
| `$iInvoiceId` | **int&#124;string** |  |





***

### scopeGetByBook



```php
public scopeGetByBook(\October\Rain\Database\Builder|self $obQuery, string|array $book): \October\Rain\Database\Builder|self
```








**Parameters:**

| Parameter | Type | Description |
|-----------|------|-------------|
| `$obQuery` | **\October\Rain\Database\Builder&#124;self** |  |
| `$book` | **string&#124;array** |  |





***

### updateAmounts



```php
public updateAmounts(): mixed
```












***


***
> Automatically generated on 2024-05-24
