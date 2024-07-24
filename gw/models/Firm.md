***

# Firm

Class Firm.



* Full name: `\PlanetaDelEste\GW\Models\Firm`
* Parent class: [`Model`](../../../Model.md)
* This class implements:
[`\OwenIt\Auditing\Contracts\Auditable`](../../../OwenIt/Auditing/Contracts/Auditable.md)


## Constants

| Constant | Visibility | Type | Value |
|:---------|:-----------|:-----|:------|
|`DOC_TYPE_RUT`|public| |&#039;rut&#039;|
|`DOC_TYPE_CI`|public| |&#039;ci&#039;|
|`DOC_TYPE_NIE`|public| |&#039;nie&#039;|
|`DOC_TYPE_PASSPORT`|public| |&#039;passport&#039;|
|`DOC_TYPE_DNI`|public| |&#039;dni&#039;|
|`DOC_TYPE_NIFE`|public| |&#039;nife&#039;|
|`DOC_TYPE_OTHER`|public| |&#039;other&#039;|

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

### morphTo



```php
public array $morphTo
```






***

### appends



```php
protected $appends
```






***

## Methods


### getCountryIdAttribute



```php
public getCountryIdAttribute(mixed $sValue): mixed
```








**Parameters:**

| Parameter | Type | Description |
|-----------|------|-------------|
| `$sValue` | **mixed** |  |




**Throws:**

- [`Exception`](../../../Exception.md)



***

### getStateIdAttribute



```php
public getStateIdAttribute(mixed $sValue): mixed
```








**Parameters:**

| Parameter | Type | Description |
|-----------|------|-------------|
| `$sValue` | **mixed** |  |




**Throws:**

- [`Exception`](../../../Exception.md)



***

### getTownIdAttribute



```php
public getTownIdAttribute(mixed $sValue): mixed
```








**Parameters:**

| Parameter | Type | Description |
|-----------|------|-------------|
| `$sValue` | **mixed** |  |




**Throws:**

- [`Exception`](../../../Exception.md)



***

### getIsLocalAttribute



```php
public getIsLocalAttribute(): bool
```











**Throws:**

- [`Exception`](../../../Exception.md)



***

### getAddressAttribute



```php
public getAddressAttribute(mixed $sValue): ?string
```








**Parameters:**

| Parameter | Type | Description |
|-----------|------|-------------|
| `$sValue` | **mixed** |  |





***

### getDgiLocNomAttribute



```php
public getDgiLocNomAttribute(mixed $sValue): mixed
```








**Parameters:**

| Parameter | Type | Description |
|-----------|------|-------------|
| `$sValue` | **mixed** |  |





***

### getDgiDptoNomAttribute



```php
public getDgiDptoNomAttribute(mixed $sValue): mixed
```








**Parameters:**

| Parameter | Type | Description |
|-----------|------|-------------|
| `$sValue` | **mixed** |  |





***

### getDgiDenominacionAttribute



```php
public getDgiDenominacionAttribute(mixed $sValue): string
```








**Parameters:**

| Parameter | Type | Description |
|-----------|------|-------------|
| `$sValue` | **mixed** |  |





***

### getDgiDirFiscalAttribute



```php
public getDgiDirFiscalAttribute(mixed $sValue): mixed
```








**Parameters:**

| Parameter | Type | Description |
|-----------|------|-------------|
| `$sValue` | **mixed** |  |





***

### getDgiDocTypeAttribute



```php
public getDgiDocTypeAttribute(): int
```












***

### getDocFormattedAttribute



```php
public getDocFormattedAttribute(): ?string
```












***

### scopeGetByCompany



```php
public scopeGetByCompany(\October\Rain\Database\Builder|static $obQuery, string $sClass, ?int $iCompanyId = null): \October\Rain\Database\Builder|static
```








**Parameters:**

| Parameter | Type | Description |
|-----------|------|-------------|
| `$obQuery` | **\October\Rain\Database\Builder&#124;static** |  |
| `$sClass` | **string** |  |
| `$iCompanyId` | **?int** |  |




**Throws:**

- [`JWTException`](../../../Tymon/JWTAuth/Exceptions/JWTException.md)



***

### beforeValidate



```php
protected beforeValidate(): mixed
```












***

### beforeSave



```php
protected beforeSave(): mixed
```












***


***
> Automatically generated on 2024-05-24
