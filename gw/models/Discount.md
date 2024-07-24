***

# Discount

Class Discount



* Full name: `\PlanetaDelEste\GW\Models\Discount`
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

### morphTo



```php
public array $morphTo
```






***

## Methods


### calculate



```php
public calculate(float& $fValue): mixed
```








**Parameters:**

| Parameter | Type | Description |
|-----------|------|-------------|
| `$fValue` | **float** |  |





***

### calculateOnly

Calculate discount value and return array with [discount value, final value with discount]

```php
public calculateOnly(float $fValue): array|float[]|int[]
```








**Parameters:**

| Parameter | Type | Description |
|-----------|------|-------------|
| `$fValue` | **float** |  |





***


***
> Automatically generated on 2024-05-24
