***

# FilterHash

Class FilterHash



* Full name: `\PlanetaDelEste\GW\Models\FilterHash`
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

### jsonable



```php
public array $jsonable
```






***

### fillable



```php
public array $fillable
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


### beforeCreate



```php
public beforeCreate(): mixed
```












***

### firstHashOrCreate



```php
public static firstHashOrCreate(array $arData = [], string|null $sClass = null): string|null
```



* This method is **static**.




**Parameters:**

| Parameter | Type | Description |
|-----------|------|-------------|
| `$arData` | **array** |  |
| `$sClass` | **string&#124;null** |  |




**Throws:**

- [`JWTException`](../../../Tymon/JWTAuth/Exceptions/JWTException.md)



***

### hash



```php
public static hash(array $arData): string|null
```



* This method is **static**.




**Parameters:**

| Parameter | Type | Description |
|-----------|------|-------------|
| `$arData` | **array** |  |





***

### scopeGetByHash



```php
public scopeGetByHash(\October\Rain\Database\Builder|self $obQuery, string $sHash): \October\Rain\Database\Builder|self
```








**Parameters:**

| Parameter | Type | Description |
|-----------|------|-------------|
| `$obQuery` | **\October\Rain\Database\Builder&#124;self** |  |
| `$sHash` | **string** |  |





***


***
> Automatically generated on 2024-05-24
