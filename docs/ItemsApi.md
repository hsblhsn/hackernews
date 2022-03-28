# \ItemsApi

All URIs are relative to *https://hacker-news.firebaseio.com/v0*

Method | HTTP request | Description
------------- | ------------- | -------------
[**GETItemItemIdJson**](ItemsApi.md#GETItemItemIdJson) | **Get** /item/{item-id}.json | Get By ID


# **GETItemItemIdJson**
> interface{} GETItemItemIdJson(ctx, itemId, optional)
Get By ID

<p>Stories, comments, jobs, Ask HNs and even polls are just items. They're identified by their ids, which are unique integers, and live under https://hacker-news.firebaseio.com/v0/item/{item-id}</p> <p>Story: https://hacker-news.firebaseio.com/v0/item/8863.json?print=pretty</p>

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **itemId** | **int32**|  | 
 **optional** | ***ItemsApiGETItemItemIdJsonOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a ItemsApiGETItemItemIdJsonOpts struct

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **print** | **optional.String**|  | [default to pretty]

### Return type

**interface{}**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

