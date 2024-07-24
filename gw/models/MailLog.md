***

# MailLog

Class MailLog



* Full name: `\PlanetaDelEste\GW\Models\MailLog`
* Parent class: [`Model`](../../../Model.md)


## Constants

| Constant | Visibility | Type | Value |
|:---------|:-----------|:-----|:------|
|`STATUS_DONE`|public| |&#039;done&#039;|
|`STATUS_ERROR`|public| |&#039;error&#039;|

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

### morphTo



```php
public array $morphTo
```






***

### attachOne



```php
public $attachOne
```






***

## Methods


### scopeGetByMailId



```php
public scopeGetByMailId(\October\Rain\Database\Builder|self $obQuery, string $sValue): \October\Rain\Database\Builder|self
```








**Parameters:**

| Parameter | Type | Description |
|-----------|------|-------------|
| `$obQuery` | **\October\Rain\Database\Builder&#124;self** |  |
| `$sValue` | **string** |  |





***

### scopeGetByInvoice



```php
public scopeGetByInvoice(\October\Rain\Database\Builder|self $obQuery, string|int $sValue): \October\Rain\Database\Builder|self
```








**Parameters:**

| Parameter | Type | Description |
|-----------|------|-------------|
| `$obQuery` | **\October\Rain\Database\Builder&#124;self** |  |
| `$sValue` | **string&#124;int** |  |





***

### getRawXmlAttribute



```php
public getRawXmlAttribute(): mixed
```












***

### getXmlAttribute



```php
public getXmlAttribute(): mixed
```












***


***
> Automatically generated on 2024-05-24
