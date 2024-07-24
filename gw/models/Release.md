***

# Release

Class Release



* Full name: `\PlanetaDelEste\GW\Models\Release`
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

### hasMany



```php
public $hasMany
```






***

## Methods


### getPreviewTextAttribute



```php
public getPreviewTextAttribute(): ?string
```












***

### scopeGetByType



```php
public scopeGetByType(\October\Rain\Database\Builder|self $obQuery, string $sType): \October\Rain\Database\Builder|self
```








**Parameters:**

| Parameter | Type | Description |
|-----------|------|-------------|
| `$obQuery` | **\October\Rain\Database\Builder&#124;self** |  |
| `$sType` | **string** |  |





***

### scopeOrderByLatestVersion



```php
public scopeOrderByLatestVersion(\October\Rain\Database\Builder|self $obQuery): \October\Rain\Database\Builder|self
```








**Parameters:**

| Parameter | Type | Description |
|-----------|------|-------------|
| `$obQuery` | **\October\Rain\Database\Builder&#124;self** |  |





***

### scopeOrderByOldestVersion



```php
public scopeOrderByOldestVersion(\October\Rain\Database\Builder|self $obQuery): \October\Rain\Database\Builder|self
```








**Parameters:**

| Parameter | Type | Description |
|-----------|------|-------------|
| `$obQuery` | **\October\Rain\Database\Builder&#124;self** |  |





***

### rawColumn



```php
public static rawColumn(): \Illuminate\Database\Query\Expression
```



* This method is **static**.








***


***
> Automatically generated on 2024-05-24
