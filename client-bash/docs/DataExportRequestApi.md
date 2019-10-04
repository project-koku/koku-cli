# DataExportRequestApi

All URIs are relative to */api/cost-management/v1*

Method | HTTP request | Description
------------- | ------------- | -------------
[**createDataExportRequest**](DataExportRequestApi.md#createDataExportRequest) | **POST** /dataexportrequests/ | Create a data export request
[**listDataExportRequests**](DataExportRequestApi.md#listDataExportRequests) | **GET** /dataexportrequests/ | List the data export requests
[**retrieveDataExportRequest**](DataExportRequestApi.md#retrieveDataExportRequest) | **GET** /dataexportrequests/{uuid}/ | Get a data export request



## createDataExportRequest

Create a data export request

### Example

```bash
 createDataExportRequest
```

### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **dataExportRequest** | [**DataExportRequest**](DataExportRequest.md) | Data export request to create |

### Return type

[**DataExportRequestOut**](DataExportRequestOut.md)

### Authorization

[basic_auth](../README.md#basic_auth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## listDataExportRequests

List the data export requests

### Example

```bash
 listDataExportRequests  offset=value  limit=value
```

### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **offset** | **integer** | Parameter for selecting the offset of data. | [optional] [default to 0]
 **limit** | **integer** | Parameter for selecting the amount of data in a returned. | [optional] [default to 10]

### Return type

[**DataExportRequestPagination**](DataExportRequestPagination.md)

### Authorization

[basic_auth](../README.md#basic_auth)

### HTTP request headers

- **Content-Type**: Not Applicable
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## retrieveDataExportRequest

Get a data export request

### Example

```bash
 retrieveDataExportRequest uuid=value
```

### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **uuid** | [**string**](.md) | ID of data export request to get | [default to null]

### Return type

[**DataExportRequestOut**](DataExportRequestOut.md)

### Authorization

[basic_auth](../README.md#basic_auth)

### HTTP request headers

- **Content-Type**: Not Applicable
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

