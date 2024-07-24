***

# PaymentMethod

Class PaymentMethod



* Full name: `\PlanetaDelEste\GW\Models\PaymentMethod`
* Parent class: [`Model`](../../../Model.md)


## Constants

| Constant | Visibility | Type | Value |
|:---------|:-----------|:-----|:------|
|`CODE_CASH`|public| |&#039;EFECTIVO&#039;|
|`CODE_CHECK`|public| |&#039;CHEQUE&#039;|
|`CODE_CREDITCARD`|public| |&#039;TARJETA&#039;|
|`CODE_BANK_ACCOUNT`|public| |&#039;CUENTA_BANCARIA&#039;|
|`CODE_CERTIFICATE`|public| |&#039;CERTIFICADO&#039;|
|`CODE_RESGUARD`|public| |&#039;RESGUARDO&#039;|
|`CODE_AGREED`|public| |&#039;CONFORME&#039;|
|`CODE_NONE`|public| |&#039;NINGUNO&#039;|

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

### translatable



```php
public array $translatable
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

### casts



```php
protected string[] $casts
```






***

## Methods


### scopeInAccount



```php
public scopeInAccount(\October\Rain\Database\Builder|self $obQuery): \October\Rain\Database\Builder|self
```








**Parameters:**

| Parameter | Type | Description |
|-----------|------|-------------|
| `$obQuery` | **\October\Rain\Database\Builder&#124;self** |  |





***

### scopeNotInAccount



```php
public scopeNotInAccount(\October\Rain\Database\Builder|self $obQuery): \October\Rain\Database\Builder|self
```








**Parameters:**

| Parameter | Type | Description |
|-----------|------|-------------|
| `$obQuery` | **\October\Rain\Database\Builder&#124;self** |  |





***

### scopeInInvoice



```php
public scopeInInvoice(\October\Rain\Database\Builder|self $obQuery): \October\Rain\Database\Builder|self
```








**Parameters:**

| Parameter | Type | Description |
|-----------|------|-------------|
| `$obQuery` | **\October\Rain\Database\Builder&#124;self** |  |





***

### scopeNotInInvoice



```php
public scopeNotInInvoice(\October\Rain\Database\Builder|self $obQuery): \October\Rain\Database\Builder|self
```








**Parameters:**

| Parameter | Type | Description |
|-----------|------|-------------|
| `$obQuery` | **\October\Rain\Database\Builder&#124;self** |  |





***

### scopeConfigurable



```php
public scopeConfigurable(\October\Rain\Database\Builder|self $obQuery): \October\Rain\Database\Builder|self
```








**Parameters:**

| Parameter | Type | Description |
|-----------|------|-------------|
| `$obQuery` | **\October\Rain\Database\Builder&#124;self** |  |





***

### scopeNotConfigurable



```php
public scopeNotConfigurable(\October\Rain\Database\Builder|self $obQuery): \October\Rain\Database\Builder|self
```








**Parameters:**

| Parameter | Type | Description |
|-----------|------|-------------|
| `$obQuery` | **\October\Rain\Database\Builder&#124;self** |  |





***

### scopeGetByCash



```php
public scopeGetByCash(\October\Rain\Database\Builder|self $obQuery): \October\Rain\Database\Builder|self
```








**Parameters:**

| Parameter | Type | Description |
|-----------|------|-------------|
| `$obQuery` | **\October\Rain\Database\Builder&#124;self** |  |





***


***
> Automatically generated on 2024-05-24
