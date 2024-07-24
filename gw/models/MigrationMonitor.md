***

# MigrationMonitor

Class MigrationMonitor



* Full name: `\PlanetaDelEste\GW\Models\MigrationMonitor`
* Parent class: [`Model`](../../../Model.md)



## Properties


### table



```php
public string $table
```






***

### attributeNames



```php
public $attributeNames
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
public array $hasMany
```






***

### belongsTo



```php
public array $belongsTo
```






***

## Methods


### getProgressAttribute



```php
public getProgressAttribute(): float
```












***

### getLoadingAttribute



```php
public getLoadingAttribute(): bool
```












***

### getCompletedAttribute



```php
public getCompletedAttribute(): bool
```












***

### setLoading

Increase processing counter

```php
public setLoading(): $this
```












***

### setLoaded

Decrease processing counter

```php
public setLoaded(): $this
```












***

### resetLoading

Reset processing counter

```php
public resetLoading(): $this
```












***


***
> Automatically generated on 2024-05-24
