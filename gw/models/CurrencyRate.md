***

# CurrencyRate

Class CurrencyRate



* Full name: `\PlanetaDelEste\GW\Models\CurrencyRate`
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

### cachePrefix



```php
public $cachePrefix
```






***

### cacheDriver



```php
public $cacheDriver
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

### casts



```php
protected $casts
```






***

## Methods


### getEditableAttribute



```php
public getEditableAttribute(): bool
```











**Throws:**

- [`JWTException`](../../../Tymon/JWTAuth/Exceptions/JWTException.md)



***

### getCodeAccountAttribute



```php
public getCodeAccountAttribute(): ?string
```












***

### scopeGetByCurrency



```php
public scopeGetByCurrency(\October\Rain\Database\Builder|self $obQuery, int|int[] $iCurrencyId): \October\Rain\Database\Builder|self
```








**Parameters:**

| Parameter | Type | Description |
|-----------|------|-------------|
| `$obQuery` | **\October\Rain\Database\Builder&#124;self** |  |
| `$iCurrencyId` | **int&#124;int[]** |  |





***

### scopeGetByDefault



```php
public scopeGetByDefault(\October\Rain\Database\Builder|self $obQuery): \October\Rain\Database\Builder|self
```








**Parameters:**

| Parameter | Type | Description |
|-----------|------|-------------|
| `$obQuery` | **\October\Rain\Database\Builder&#124;self** |  |





***

### scopeGetByCode



```php
public scopeGetByCode(\October\Rain\Database\Builder|self $obQuery, string $sCode): \October\Rain\Database\Builder|self
```








**Parameters:**

| Parameter | Type | Description |
|-----------|------|-------------|
| `$obQuery` | **\October\Rain\Database\Builder&#124;self** |  |
| `$sCode` | **string** |  |





***

### scopeGroupByCurrency



```php
public scopeGroupByCurrency(\October\Rain\Database\Builder|self $obQuery): \October\Rain\Database\Builder|self
```








**Parameters:**

| Parameter | Type | Description |
|-----------|------|-------------|
| `$obQuery` | **\October\Rain\Database\Builder&#124;self** |  |





***

### scopeWithRYACode



```php
public scopeWithRYACode(\October\Rain\Database\Builder|self $obQuery): \October\Rain\Database\Builder|self
```








**Parameters:**

| Parameter | Type | Description |
|-----------|------|-------------|
| `$obQuery` | **\October\Rain\Database\Builder&#124;self** |  |





***

### getRoundAttribute



```php
public getRoundAttribute(int|float $sValue): int
```








**Parameters:**

| Parameter | Type | Description |
|-----------|------|-------------|
| `$sValue` | **int&#124;float** |  |





***

### beforeSave



```php
protected beforeSave(): mixed
```












***

### setRateAttribute

Set rate attribute

```php
protected setRateAttribute(string|float $sValue): mixed
```








**Parameters:**

| Parameter | Type | Description |
|-----------|------|-------------|
| `$sValue` | **string&#124;float** |  |





***


***
> Automatically generated on 2024-05-24
