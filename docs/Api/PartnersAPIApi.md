# OpenAPI\Client\PartnersAPIApi



All URIs are relative to https://api-sandbox.ubiqfy.com, except if the operation defines another base path.

| Method | HTTP request | Description |
| ------------- | ------------- | ------------- |
| [**partnersAPIAuthenticate()**](PartnersAPIApi.md#partnersAPIAuthenticate) | **POST** /Authenticate |  |
| [**partnersAPICancelTransaction()**](PartnersAPIApi.md#partnersAPICancelTransaction) | **POST** /CancelTransaction |  |
| [**partnersAPIDoCalculateEstimatePrice()**](PartnersAPIApi.md#partnersAPIDoCalculateEstimatePrice) | **POST** /DoCalculateEstimatePrice |  |
| [**partnersAPIDoTransaction()**](PartnersAPIApi.md#partnersAPIDoTransaction) | **POST** /DoTransaction |  |
| [**partnersAPIGetAvailableProduct()**](PartnersAPIApi.md#partnersAPIGetAvailableProduct) | **POST** /GetAvailableProduct |  |
| [**partnersAPIGetAvailableProductByCode()**](PartnersAPIApi.md#partnersAPIGetAvailableProductByCode) | **POST** /GetAvailableProductByCode |  |
| [**partnersAPIGetAvailableProductOptionByCode()**](PartnersAPIApi.md#partnersAPIGetAvailableProductOptionByCode) | **POST** /GetAvailableProductOptionByCode |  |
| [**partnersAPIGetAvailableProductTypes()**](PartnersAPIApi.md#partnersAPIGetAvailableProductTypes) | **POST** /GetAvailableProductTypes |  |
| [**partnersAPIGetCountries()**](PartnersAPIApi.md#partnersAPIGetCountries) | **POST** /GetCountries |  |
| [**partnersAPIGetInternationalMobileProducts()**](PartnersAPIApi.md#partnersAPIGetInternationalMobileProducts) | **POST** /GetInternationalMobileProducts |  |
| [**partnersAPIGetInternationalOperators()**](PartnersAPIApi.md#partnersAPIGetInternationalOperators) | **POST** /GetInternationalOperators |  |
| [**partnersAPIGetInternationalPhoneNumberOptions()**](PartnersAPIApi.md#partnersAPIGetInternationalPhoneNumberOptions) | **POST** /GetInternationalPhoneNumberOptions |  |
| [**partnersAPIGetProductOptionPhoneNumber()**](PartnersAPIApi.md#partnersAPIGetProductOptionPhoneNumber) | **POST** /GetProductOptionPhoneNumber |  |
| [**partnersAPIGetTransaction()**](PartnersAPIApi.md#partnersAPIGetTransaction) | **POST** /GetTransaction |  |


## `partnersAPIAuthenticate()`

```php
partnersAPIAuthenticate($request): \OpenAPI\Client\Model\AuthenticateResponse
```



### Example

```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');



$apiInstance = new OpenAPI\Client\Api\PartnersAPIApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);
$request = new \OpenAPI\Client\Model\AuthenticateRequest(); // \OpenAPI\Client\Model\AuthenticateRequest

try {
    $result = $apiInstance->partnersAPIAuthenticate($request);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling PartnersAPIApi->partnersAPIAuthenticate: ', $e->getMessage(), PHP_EOL;
}
```

### Parameters

| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
| **request** | [**\OpenAPI\Client\Model\AuthenticateRequest**](../Model/AuthenticateRequest.md)|  | |

### Return type

[**\OpenAPI\Client\Model\AuthenticateResponse**](../Model/AuthenticateResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: `application/json`, `text/json`, `application/xml`, `text/xml`, `application/x-www-form-urlencoded`
- **Accept**: `application/json`, `text/json`, `application/xml`, `text/xml`

[[Back to top]](#) [[Back to API list]](../../README.md#endpoints)
[[Back to Model list]](../../README.md#models)
[[Back to README]](../../README.md)

## `partnersAPICancelTransaction()`

```php
partnersAPICancelTransaction($request): \OpenAPI\Client\Model\APICancelTransactionResponse
```



### Example

```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');



$apiInstance = new OpenAPI\Client\Api\PartnersAPIApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);
$request = new \OpenAPI\Client\Model\APICancelTransactionRequest(); // \OpenAPI\Client\Model\APICancelTransactionRequest

try {
    $result = $apiInstance->partnersAPICancelTransaction($request);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling PartnersAPIApi->partnersAPICancelTransaction: ', $e->getMessage(), PHP_EOL;
}
```

### Parameters

| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
| **request** | [**\OpenAPI\Client\Model\APICancelTransactionRequest**](../Model/APICancelTransactionRequest.md)|  | |

### Return type

[**\OpenAPI\Client\Model\APICancelTransactionResponse**](../Model/APICancelTransactionResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: `application/json`, `text/json`, `application/xml`, `text/xml`, `application/x-www-form-urlencoded`
- **Accept**: `application/json`, `text/json`, `application/xml`, `text/xml`

[[Back to top]](#) [[Back to API list]](../../README.md#endpoints)
[[Back to Model list]](../../README.md#models)
[[Back to README]](../../README.md)

## `partnersAPIDoCalculateEstimatePrice()`

```php
partnersAPIDoCalculateEstimatePrice($request): \OpenAPI\Client\Model\CalculateEstimatePriceResponse
```



### Example

```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');



$apiInstance = new OpenAPI\Client\Api\PartnersAPIApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);
$request = new \OpenAPI\Client\Model\CalculateEstimatePriceRequest(); // \OpenAPI\Client\Model\CalculateEstimatePriceRequest

try {
    $result = $apiInstance->partnersAPIDoCalculateEstimatePrice($request);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling PartnersAPIApi->partnersAPIDoCalculateEstimatePrice: ', $e->getMessage(), PHP_EOL;
}
```

### Parameters

| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
| **request** | [**\OpenAPI\Client\Model\CalculateEstimatePriceRequest**](../Model/CalculateEstimatePriceRequest.md)|  | |

### Return type

[**\OpenAPI\Client\Model\CalculateEstimatePriceResponse**](../Model/CalculateEstimatePriceResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: `application/json`, `text/json`, `application/xml`, `text/xml`, `application/x-www-form-urlencoded`
- **Accept**: `application/json`, `text/json`, `application/xml`, `text/xml`

[[Back to top]](#) [[Back to API list]](../../README.md#endpoints)
[[Back to Model list]](../../README.md#models)
[[Back to README]](../../README.md)

## `partnersAPIDoTransaction()`

```php
partnersAPIDoTransaction($request): \OpenAPI\Client\Model\ApplyTransactionResponse
```



### Example

```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');



$apiInstance = new OpenAPI\Client\Api\PartnersAPIApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);
$request = new \OpenAPI\Client\Model\ApplyTransactionRequest(); // \OpenAPI\Client\Model\ApplyTransactionRequest

try {
    $result = $apiInstance->partnersAPIDoTransaction($request);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling PartnersAPIApi->partnersAPIDoTransaction: ', $e->getMessage(), PHP_EOL;
}
```

### Parameters

| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
| **request** | [**\OpenAPI\Client\Model\ApplyTransactionRequest**](../Model/ApplyTransactionRequest.md)|  | |

### Return type

[**\OpenAPI\Client\Model\ApplyTransactionResponse**](../Model/ApplyTransactionResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: `application/json`, `text/json`, `application/xml`, `text/xml`, `application/x-www-form-urlencoded`
- **Accept**: `application/json`, `text/json`, `application/xml`, `text/xml`

[[Back to top]](#) [[Back to API list]](../../README.md#endpoints)
[[Back to Model list]](../../README.md#models)
[[Back to README]](../../README.md)

## `partnersAPIGetAvailableProduct()`

```php
partnersAPIGetAvailableProduct($request): \OpenAPI\Client\Model\AvailableProductsResponse
```



### Example

```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');



$apiInstance = new OpenAPI\Client\Api\PartnersAPIApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);
$request = new \OpenAPI\Client\Model\AvailableProductsRequest(); // \OpenAPI\Client\Model\AvailableProductsRequest

try {
    $result = $apiInstance->partnersAPIGetAvailableProduct($request);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling PartnersAPIApi->partnersAPIGetAvailableProduct: ', $e->getMessage(), PHP_EOL;
}
```

### Parameters

| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
| **request** | [**\OpenAPI\Client\Model\AvailableProductsRequest**](../Model/AvailableProductsRequest.md)|  | |

### Return type

[**\OpenAPI\Client\Model\AvailableProductsResponse**](../Model/AvailableProductsResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: `application/json`, `text/json`, `application/xml`, `text/xml`, `application/x-www-form-urlencoded`
- **Accept**: `application/json`, `text/json`, `application/xml`, `text/xml`

[[Back to top]](#) [[Back to API list]](../../README.md#endpoints)
[[Back to Model list]](../../README.md#models)
[[Back to README]](../../README.md)

## `partnersAPIGetAvailableProductByCode()`

```php
partnersAPIGetAvailableProductByCode($request): \OpenAPI\Client\Model\AvailableProductResponse
```



### Example

```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');



$apiInstance = new OpenAPI\Client\Api\PartnersAPIApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);
$request = new \OpenAPI\Client\Model\AvailableProductRequest(); // \OpenAPI\Client\Model\AvailableProductRequest

try {
    $result = $apiInstance->partnersAPIGetAvailableProductByCode($request);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling PartnersAPIApi->partnersAPIGetAvailableProductByCode: ', $e->getMessage(), PHP_EOL;
}
```

### Parameters

| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
| **request** | [**\OpenAPI\Client\Model\AvailableProductRequest**](../Model/AvailableProductRequest.md)|  | |

### Return type

[**\OpenAPI\Client\Model\AvailableProductResponse**](../Model/AvailableProductResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: `application/json`, `text/json`, `application/xml`, `text/xml`, `application/x-www-form-urlencoded`
- **Accept**: `application/json`, `text/json`, `application/xml`, `text/xml`

[[Back to top]](#) [[Back to API list]](../../README.md#endpoints)
[[Back to Model list]](../../README.md#models)
[[Back to README]](../../README.md)

## `partnersAPIGetAvailableProductOptionByCode()`

```php
partnersAPIGetAvailableProductOptionByCode($request): \OpenAPI\Client\Model\AvailableProductOptionByCodeResponse
```



### Example

```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');



$apiInstance = new OpenAPI\Client\Api\PartnersAPIApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);
$request = new \OpenAPI\Client\Model\AvailableProductOptionByCodeRequest(); // \OpenAPI\Client\Model\AvailableProductOptionByCodeRequest

try {
    $result = $apiInstance->partnersAPIGetAvailableProductOptionByCode($request);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling PartnersAPIApi->partnersAPIGetAvailableProductOptionByCode: ', $e->getMessage(), PHP_EOL;
}
```

### Parameters

| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
| **request** | [**\OpenAPI\Client\Model\AvailableProductOptionByCodeRequest**](../Model/AvailableProductOptionByCodeRequest.md)|  | |

### Return type

[**\OpenAPI\Client\Model\AvailableProductOptionByCodeResponse**](../Model/AvailableProductOptionByCodeResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: `application/json`, `text/json`, `application/xml`, `text/xml`, `application/x-www-form-urlencoded`
- **Accept**: `application/json`, `text/json`, `application/xml`, `text/xml`

[[Back to top]](#) [[Back to API list]](../../README.md#endpoints)
[[Back to Model list]](../../README.md#models)
[[Back to README]](../../README.md)

## `partnersAPIGetAvailableProductTypes()`

```php
partnersAPIGetAvailableProductTypes($request): \OpenAPI\Client\Model\AvailableProductTypesResponse
```



### Example

```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');



$apiInstance = new OpenAPI\Client\Api\PartnersAPIApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);
$request = new \OpenAPI\Client\Model\AvailableProductTypesRequest(); // \OpenAPI\Client\Model\AvailableProductTypesRequest

try {
    $result = $apiInstance->partnersAPIGetAvailableProductTypes($request);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling PartnersAPIApi->partnersAPIGetAvailableProductTypes: ', $e->getMessage(), PHP_EOL;
}
```

### Parameters

| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
| **request** | [**\OpenAPI\Client\Model\AvailableProductTypesRequest**](../Model/AvailableProductTypesRequest.md)|  | |

### Return type

[**\OpenAPI\Client\Model\AvailableProductTypesResponse**](../Model/AvailableProductTypesResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: `application/json`, `text/json`, `application/xml`, `text/xml`, `application/x-www-form-urlencoded`
- **Accept**: `application/json`, `text/json`, `application/xml`, `text/xml`

[[Back to top]](#) [[Back to API list]](../../README.md#endpoints)
[[Back to Model list]](../../README.md#models)
[[Back to README]](../../README.md)

## `partnersAPIGetCountries()`

```php
partnersAPIGetCountries($request): \OpenAPI\Client\Model\AvailableCountriesResponse
```



### Example

```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');



$apiInstance = new OpenAPI\Client\Api\PartnersAPIApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);
$request = new \OpenAPI\Client\Model\AvailableCountriesRequest(); // \OpenAPI\Client\Model\AvailableCountriesRequest

try {
    $result = $apiInstance->partnersAPIGetCountries($request);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling PartnersAPIApi->partnersAPIGetCountries: ', $e->getMessage(), PHP_EOL;
}
```

### Parameters

| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
| **request** | [**\OpenAPI\Client\Model\AvailableCountriesRequest**](../Model/AvailableCountriesRequest.md)|  | |

### Return type

[**\OpenAPI\Client\Model\AvailableCountriesResponse**](../Model/AvailableCountriesResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: `application/json`, `text/json`, `application/xml`, `text/xml`, `application/x-www-form-urlencoded`
- **Accept**: `application/json`, `text/json`, `application/xml`, `text/xml`

[[Back to top]](#) [[Back to API list]](../../README.md#endpoints)
[[Back to Model list]](../../README.md#models)
[[Back to README]](../../README.md)

## `partnersAPIGetInternationalMobileProducts()`

```php
partnersAPIGetInternationalMobileProducts($request): \OpenAPI\Client\Model\AvailableInternationalMobileProductsResponse
```



### Example

```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');



$apiInstance = new OpenAPI\Client\Api\PartnersAPIApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);
$request = new \OpenAPI\Client\Model\AvailableInternationalMobileProductsRequest(); // \OpenAPI\Client\Model\AvailableInternationalMobileProductsRequest

try {
    $result = $apiInstance->partnersAPIGetInternationalMobileProducts($request);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling PartnersAPIApi->partnersAPIGetInternationalMobileProducts: ', $e->getMessage(), PHP_EOL;
}
```

### Parameters

| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
| **request** | [**\OpenAPI\Client\Model\AvailableInternationalMobileProductsRequest**](../Model/AvailableInternationalMobileProductsRequest.md)|  | |

### Return type

[**\OpenAPI\Client\Model\AvailableInternationalMobileProductsResponse**](../Model/AvailableInternationalMobileProductsResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: `application/json`, `text/json`, `application/xml`, `text/xml`, `application/x-www-form-urlencoded`
- **Accept**: `application/json`, `text/json`, `application/xml`, `text/xml`

[[Back to top]](#) [[Back to API list]](../../README.md#endpoints)
[[Back to Model list]](../../README.md#models)
[[Back to README]](../../README.md)

## `partnersAPIGetInternationalOperators()`

```php
partnersAPIGetInternationalOperators($request): \OpenAPI\Client\Model\AvailableInternationalOperatorsResponse
```



### Example

```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');



$apiInstance = new OpenAPI\Client\Api\PartnersAPIApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);
$request = new \OpenAPI\Client\Model\AvailableInternationalOperatorsRequest(); // \OpenAPI\Client\Model\AvailableInternationalOperatorsRequest

try {
    $result = $apiInstance->partnersAPIGetInternationalOperators($request);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling PartnersAPIApi->partnersAPIGetInternationalOperators: ', $e->getMessage(), PHP_EOL;
}
```

### Parameters

| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
| **request** | [**\OpenAPI\Client\Model\AvailableInternationalOperatorsRequest**](../Model/AvailableInternationalOperatorsRequest.md)|  | |

### Return type

[**\OpenAPI\Client\Model\AvailableInternationalOperatorsResponse**](../Model/AvailableInternationalOperatorsResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: `application/json`, `text/json`, `application/xml`, `text/xml`, `application/x-www-form-urlencoded`
- **Accept**: `application/json`, `text/json`, `application/xml`, `text/xml`

[[Back to top]](#) [[Back to API list]](../../README.md#endpoints)
[[Back to Model list]](../../README.md#models)
[[Back to README]](../../README.md)

## `partnersAPIGetInternationalPhoneNumberOptions()`

```php
partnersAPIGetInternationalPhoneNumberOptions($request): \OpenAPI\Client\Model\GetInternationalPhoneNumberOptionsResponse
```



### Example

```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');



$apiInstance = new OpenAPI\Client\Api\PartnersAPIApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);
$request = new \OpenAPI\Client\Model\GetInternationalPhoneNumberOptionsRequest(); // \OpenAPI\Client\Model\GetInternationalPhoneNumberOptionsRequest

try {
    $result = $apiInstance->partnersAPIGetInternationalPhoneNumberOptions($request);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling PartnersAPIApi->partnersAPIGetInternationalPhoneNumberOptions: ', $e->getMessage(), PHP_EOL;
}
```

### Parameters

| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
| **request** | [**\OpenAPI\Client\Model\GetInternationalPhoneNumberOptionsRequest**](../Model/GetInternationalPhoneNumberOptionsRequest.md)|  | |

### Return type

[**\OpenAPI\Client\Model\GetInternationalPhoneNumberOptionsResponse**](../Model/GetInternationalPhoneNumberOptionsResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: `application/json`, `text/json`, `application/xml`, `text/xml`, `application/x-www-form-urlencoded`
- **Accept**: `application/json`, `text/json`, `application/xml`, `text/xml`

[[Back to top]](#) [[Back to API list]](../../README.md#endpoints)
[[Back to Model list]](../../README.md#models)
[[Back to README]](../../README.md)

## `partnersAPIGetProductOptionPhoneNumber()`

```php
partnersAPIGetProductOptionPhoneNumber($request): \OpenAPI\Client\Model\AvailableProductOptionResponse
```



### Example

```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');



$apiInstance = new OpenAPI\Client\Api\PartnersAPIApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);
$request = new \OpenAPI\Client\Model\AvailableProductOptionRequest(); // \OpenAPI\Client\Model\AvailableProductOptionRequest

try {
    $result = $apiInstance->partnersAPIGetProductOptionPhoneNumber($request);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling PartnersAPIApi->partnersAPIGetProductOptionPhoneNumber: ', $e->getMessage(), PHP_EOL;
}
```

### Parameters

| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
| **request** | [**\OpenAPI\Client\Model\AvailableProductOptionRequest**](../Model/AvailableProductOptionRequest.md)|  | |

### Return type

[**\OpenAPI\Client\Model\AvailableProductOptionResponse**](../Model/AvailableProductOptionResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: `application/json`, `text/json`, `application/xml`, `text/xml`, `application/x-www-form-urlencoded`
- **Accept**: `application/json`, `text/json`, `application/xml`, `text/xml`

[[Back to top]](#) [[Back to API list]](../../README.md#endpoints)
[[Back to Model list]](../../README.md#models)
[[Back to README]](../../README.md)

## `partnersAPIGetTransaction()`

```php
partnersAPIGetTransaction($request): \OpenAPI\Client\Model\GetTransactionResponse
```



### Example

```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');



$apiInstance = new OpenAPI\Client\Api\PartnersAPIApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);
$request = new \OpenAPI\Client\Model\GetTransactionRequest(); // \OpenAPI\Client\Model\GetTransactionRequest

try {
    $result = $apiInstance->partnersAPIGetTransaction($request);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling PartnersAPIApi->partnersAPIGetTransaction: ', $e->getMessage(), PHP_EOL;
}
```

### Parameters

| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
| **request** | [**\OpenAPI\Client\Model\GetTransactionRequest**](../Model/GetTransactionRequest.md)|  | |

### Return type

[**\OpenAPI\Client\Model\GetTransactionResponse**](../Model/GetTransactionResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: `application/json`, `text/json`, `application/xml`, `text/xml`, `application/x-www-form-urlencoded`
- **Accept**: `application/json`, `text/json`, `application/xml`, `text/xml`

[[Back to top]](#) [[Back to API list]](../../README.md#endpoints)
[[Back to Model list]](../../README.md#models)
[[Back to README]](../../README.md)
