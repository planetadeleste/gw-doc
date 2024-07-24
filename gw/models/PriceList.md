***

# PriceList

Class PriceList



* Full name: `\PlanetaDelEste\GW\Models\PriceList`
* Parent class: [`Model`](../../../Model.md)
* This class implements:
[`\OwenIt\Auditing\Contracts\Auditable`](../../../OwenIt/Auditing/Contracts/Auditable.md)


## Constants

| Constant | Visibility | Type | Value |
|:---------|:-----------|:-----|:------|
|`PARENT_ID`|public| |&#039;price_list_id&#039;|

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

### slugs



```php
public array $slugs
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


### setDefault

Set price list as default

```php
public setDefault(): void
```












***

### beforeSave



```php
protected beforeSave(): void
```












***

### scopeGetByOffer



```php
public scopeGetByOffer(\October\Rain\Database\Builder|static $obQuery, int|int[]|\Lovata\Shopaholic\Models\Offer $iOffer): \October\Rain\Database\Builder|static
```








**Parameters:**

| Parameter | Type | Description |
|-----------|------|-------------|
| `$obQuery` | **\October\Rain\Database\Builder&#124;static** |  |
| `$iOffer` | **int&#124;int[]&#124;\Lovata\Shopaholic\Models\Offer** |  |





***

### scopeGetByDefault



```php
public scopeGetByDefault(\October\Rain\Database\Builder|static $obQuery): \October\Rain\Database\Builder|static
```








**Parameters:**

| Parameter | Type | Description |
|-----------|------|-------------|
| `$obQuery` | **\October\Rain\Database\Builder&#124;static** |  |





***


***
> Automatically generated on 2024-05-24
