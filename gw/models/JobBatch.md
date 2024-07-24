***

# JobBatch

Class JobBatch



* Full name: `\PlanetaDelEste\GW\Models\JobBatch`
* Parent class: [`Model`](../../../Model.md)



## Properties


### table



```php
public string $table
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
public $belongsTo
```






***

## Methods


### getProgressAttribute



```php
public getProgressAttribute(): float
```












***

### getFinishedAttribute



```php
public getFinishedAttribute(): bool
```












***

### getCancelledAttribute



```php
public getCancelledAttribute(): bool
```












***

### cancel



```php
public cancel(): mixed
```












***

### finish



```php
public finish(): mixed
```












***


***
> Automatically generated on 2024-05-24
