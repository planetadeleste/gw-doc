***

# OldAccountImport





* Full name: `\PlanetaDelEste\GW\Models\OldAccountImport`
* Parent class: [`ImportModel`](../../../Backend/Models/ImportModel.md)



## Properties


### rules



```php
public $rules
```






***

### arCurrencyList



```php
protected array $arCurrencyList
```






***

### arCurrency



```php
protected array $arCurrency
```






***

## Methods


### importData



```php
public importData(mixed $results, mixed $sessionKey = null): mixed
```








**Parameters:**

| Parameter | Type | Description |
|-----------|------|-------------|
| `$results` | **mixed** |  |
| `$sessionKey` | **mixed** |  |




**Throws:**

- [`ModelException`](../../../October/Rain/Database/ModelException.md)



***

### currency



```php
protected currency(string $sCode): ?\PlanetaDelEste\GW\Classes\Database\GW\IsoMoneda
```








**Parameters:**

| Parameter | Type | Description |
|-----------|------|-------------|
| `$sCode` | **string** |  |





***

### getEmpresaIdOptions



```php
public getEmpresaIdOptions(): mixed
```












***


***
> Automatically generated on 2024-05-24
