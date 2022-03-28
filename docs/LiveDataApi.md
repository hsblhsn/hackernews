# \LiveDataApi

All URIs are relative to *https://hacker-news.firebaseio.com/v0*

Method | HTTP request | Description
------------- | ------------- | -------------
[**GETAskstoriesJson**](LiveDataApi.md#GETAskstoriesJson) | **Get** /askstories.json | Ask HN Stories
[**GETJobstoriesJson**](LiveDataApi.md#GETJobstoriesJson) | **Get** /jobstories.json | Job HN Stories
[**GETMaxitemJson**](LiveDataApi.md#GETMaxitemJson) | **Get** /maxitem.json | Max Item ID
[**GETShowstoriesJson**](LiveDataApi.md#GETShowstoriesJson) | **Get** /showstories.json | Show HN Stories
[**GETTopstoriesJson**](LiveDataApi.md#GETTopstoriesJson) | **Get** /topstories.json | New and Top Stories
[**GETUpdatesJson**](LiveDataApi.md#GETUpdatesJson) | **Get** /updates.json | Changed Items and Profiles


# **GETAskstoriesJson**
> []int32 GETAskstoriesJson(ctx, optional)
Ask HN Stories

<p>Up to 200 of the latest Ask HN Stories!</p>

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
 **optional** | ***LiveDataApiGETAskstoriesJsonOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a LiveDataApiGETAskstoriesJsonOpts struct

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **print** | **optional.String**|  | [default to prett]

### Return type

**[]int32**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GETJobstoriesJson**
> []int32 GETJobstoriesJson(ctx, optional)
Job HN Stories

<p>Up to 200 of the latest Job Stories!</p>

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
 **optional** | ***LiveDataApiGETJobstoriesJsonOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a LiveDataApiGETJobstoriesJsonOpts struct

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **print** | **optional.String**|  | [default to pretty]

### Return type

**[]int32**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GETMaxitemJson**
> int32 GETMaxitemJson(ctx, optional)
Max Item ID

<p>The current largest item id is at https://hacker-news.firebaseio.com/v0/maxitem. You can walk backward from here to discover all items.</p>

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
 **optional** | ***LiveDataApiGETMaxitemJsonOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a LiveDataApiGETMaxitemJsonOpts struct

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **print** | **optional.String**|  | [default to pretty]

### Return type

**int32**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GETShowstoriesJson**
> []int32 GETShowstoriesJson(ctx, optional)
Show HN Stories

<p>Up to 200 of the latest Show HN Stories!</p>

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
 **optional** | ***LiveDataApiGETShowstoriesJsonOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a LiveDataApiGETShowstoriesJsonOpts struct

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **print** | **optional.String**|  | [default to pretty]

### Return type

**[]int32**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GETTopstoriesJson**
> []int32 GETTopstoriesJson(ctx, optional)
New and Top Stories

<p>Up to 500 top and new stories are at https://hacker-news.firebaseio.com/v0/topstories and https://hacker-news.firebaseio.com/v0/newstories.</p>

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
 **optional** | ***LiveDataApiGETTopstoriesJsonOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a LiveDataApiGETTopstoriesJsonOpts struct

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **print** | **optional.String**|  | [default to pretty]

### Return type

**[]int32**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GETUpdatesJson**
> interface{} GETUpdatesJson(ctx, optional)
Changed Items and Profiles

<p>The item and profile changes are at https://hacker-news.firebaseio.com/v0/updates.</p> <p>Example: https://hacker-news.firebaseio.com/v0/updates.json?print=pretty</p>

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
 **optional** | ***LiveDataApiGETUpdatesJsonOpts** | optional parameters | nil if no parameters

### Optional Parameters
Optional parameters are passed through a pointer to a LiveDataApiGETUpdatesJsonOpts struct

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

