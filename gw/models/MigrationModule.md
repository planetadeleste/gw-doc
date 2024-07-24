***

# MigrationModule

Class MigrationModule.



* Full name: `\PlanetaDelEste\GW\Models\MigrationModule`
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

### casts



```php
protected $casts
```






***

## Methods


### getNameAttribute



```php
public getNameAttribute(): mixed
```












***

### getProgressAttribute



```php
public getProgressAttribute(): float
```












***

### getCreationTasksProgressAttribute



```php
public getCreationTasksProgressAttribute(): mixed
```












***

### getCompletedAttribute



```php
public getCompletedAttribute(): bool
```












***

### getModuleTypeOptions



```php
public getModuleTypeOptions(): array
```












***

### createTasks



```php
public createTasks(bool $clear = false): void
```








**Parameters:**

| Parameter | Type | Description |
|-----------|------|-------------|
| `$clear` | **bool** |  |




**Throws:**

- [`BindingResolutionException`](../../../Illuminate/Contracts/Container/BindingResolutionException.md)

- [`Exception`](../../../Exception.md)



***

### updateCounter



```php
public updateCounter(): mixed
```












***

### scopeGetByMonitor



```php
public scopeGetByMonitor(\October\Rain\Database\Builder|self $obQuery, int|string $iMonitorId): \October\Rain\Database\Builder|self
```








**Parameters:**

| Parameter | Type | Description |
|-----------|------|-------------|
| `$obQuery` | **\October\Rain\Database\Builder&#124;self** |  |
| `$iMonitorId` | **int&#124;string** |  |





***

### beforeSave



```php
protected beforeSave(): mixed
```












***


***
> Automatically generated on 2024-05-24
