***

# MigrationTask

Class MigrationTask.



* Full name: `\PlanetaDelEste\GW\Models\MigrationTask`
* Parent class: [`Model`](../../../Model.md)


## Constants

| Constant | Visibility | Type | Value |
|:---------|:-----------|:-----|:------|
|`STATUS_WAITING`|public| |&#039;waiting&#039;|
|`STATUS_COMPLETED`|public| |&#039;completed&#039;|
|`STATUS_FAILED`|public| |&#039;failed&#039;|
|`STATUS_WORKING`|public| |&#039;working&#039;|

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

### hasOneThrough



```php
public $hasOneThrough
```






***

### morphTo



```php
public $morphTo
```






***

### jsonable



```php
protected $jsonable
```






***

## Methods


### getIsCompletedAttribute



```php
public getIsCompletedAttribute(): bool
```












***

### getIsFailedAttribute



```php
public getIsFailedAttribute(): bool
```












***

### getIsWaitingAttribute



```php
public getIsWaitingAttribute(): bool
```












***

### getIsWorkingAttribute



```php
public getIsWorkingAttribute(): bool
```












***

### scopeGetByModule



```php
public scopeGetByModule(\October\Rain\Database\QueryBuilder|self $obQuery, mixed $iModuleId): \October\Rain\Database\QueryBuilder|self
```








**Parameters:**

| Parameter | Type | Description |
|-----------|------|-------------|
| `$obQuery` | **\October\Rain\Database\QueryBuilder&#124;self** |  |
| `$iModuleId` | **mixed** |  |





***

### scopeWaiting



```php
public scopeWaiting(\October\Rain\Database\QueryBuilder|self $obQuery): \October\Rain\Database\QueryBuilder|self
```








**Parameters:**

| Parameter | Type | Description |
|-----------|------|-------------|
| `$obQuery` | **\October\Rain\Database\QueryBuilder&#124;self** |  |





***

### scopeCompleted



```php
public scopeCompleted(\October\Rain\Database\QueryBuilder|self $obQuery): \October\Rain\Database\QueryBuilder|self
```








**Parameters:**

| Parameter | Type | Description |
|-----------|------|-------------|
| `$obQuery` | **\October\Rain\Database\QueryBuilder&#124;self** |  |





***

### scopeFailed



```php
public scopeFailed(\October\Rain\Database\QueryBuilder|self $obQuery): \October\Rain\Database\QueryBuilder|self
```








**Parameters:**

| Parameter | Type | Description |
|-----------|------|-------------|
| `$obQuery` | **\October\Rain\Database\QueryBuilder&#124;self** |  |





***

### getMonitor



```php
public getMonitor(string|null $sMethod = null): \PlanetaDelEste\GW\Models\MigrationMonitor|null
```








**Parameters:**

| Parameter | Type | Description |
|-----------|------|-------------|
| `$sMethod` | **string&#124;null** |  |





***

### setWaiting

Set waiting status

```php
public setWaiting(): bool
```












***

### setFailed

Set failed status

```php
public setFailed(string|null $sMessage = null): void
```








**Parameters:**

| Parameter | Type | Description |
|-----------|------|-------------|
| `$sMessage` | **string&#124;null** |  |





***

### setCompleted

Set task as completed.

```php
public setCompleted(): void
```












***

### setWorking

Set working status

```php
public setWorking(): void
```












***

### itemExists



```php
public itemExists(): bool
```












***


***
> Automatically generated on 2024-05-24
