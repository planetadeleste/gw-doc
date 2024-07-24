***

# Balance

Class Balance



* Full name: `\PlanetaDelEste\GW\Models\Balance`
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

### morphTo



```php
public array $morphTo
```






***

## Methods


### scopeGetByInvoice



```php
public scopeGetByInvoice(\October\Rain\Database\Builder|self $obQuery, int|int[]|string|string[] $iInvoiceId): \October\Rain\Database\Builder|self
```








**Parameters:**

| Parameter | Type | Description |
|-----------|------|-------------|
| `$obQuery` | **\October\Rain\Database\Builder&#124;self** |  |
| `$iInvoiceId` | **int&#124;int[]&#124;string&#124;string[]** |  |





***

### scopeGetByReference



```php
public scopeGetByReference(\October\Rain\Database\Builder|self $obQuery, int|int[]|string|string[] $iReferenceId): \October\Rain\Database\Builder|self
```








**Parameters:**

| Parameter | Type | Description |
|-----------|------|-------------|
| `$obQuery` | **\October\Rain\Database\Builder&#124;self** |  |
| `$iReferenceId` | **int&#124;int[]&#124;string&#124;string[]** |  |





***

### scopeGetBySkipBalance



```php
public scopeGetBySkipBalance(\October\Rain\Database\Builder|self $obQuery): \October\Rain\Database\Builder|self
```








**Parameters:**

| Parameter | Type | Description |
|-----------|------|-------------|
| `$obQuery` | **\October\Rain\Database\Builder&#124;self** |  |





***

### scopeGetByNotSkipBalance



```php
public scopeGetByNotSkipBalance(\October\Rain\Database\Builder|self $obQuery): \October\Rain\Database\Builder|self
```








**Parameters:**

| Parameter | Type | Description |
|-----------|------|-------------|
| `$obQuery` | **\October\Rain\Database\Builder&#124;self** |  |





***


***
> Automatically generated on 2024-05-24
