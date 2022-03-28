# \UsersApi

All URIs are relative to *https://hacker-news.firebaseio.com/v0*

Method | HTTP request | Description
------------- | ------------- | -------------
[**GETUserUserIdJson**](UsersApi.md#GETUserUserIdJson) | **Get** /user/{user-id}.json | Get User By ID


# **GETUserUserIdJson**
> interface{} GETUserUserIdJson(ctx, userId, optional)
Get User By ID

<p>Users are identified by case-sensitive ids, and live under https://hacker-news.firebaseio.com/v0/user/{user-id}. Only users that have public activity (comments or story submissions) on the site are available through the API.</p>

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **userId** | **string**|  | 
 **optional** | ***UsersApiGETUserUserIdJsonOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a UsersApiGETUserUserIdJsonOpts struct

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

