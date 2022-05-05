# \MyUserApi

All URIs are relative to *https://www/rest*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CreateUser**](MyUserApi.md#CreateUser) | **Post** /test/v1/user | 创建用户
[**DeleteUserById**](MyUserApi.md#DeleteUserById) | **Delete** /test/v1/user/{id} | 通过ID删除用户
[**GetUserById**](MyUserApi.md#GetUserById) | **Get** /test/v1/user/{id} | 通过ID获取用户信息
[**ModifyUser**](MyUserApi.md#ModifyUser) | **Put** /test/v1/user | 修改用户


# **CreateUser**
> CreateUser(ctx, user)
创建用户

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **user** | [**User**](User.md)| 创建用户 | 

### Return type

 (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **DeleteUserById**
> DeleteUserById(ctx, id)
通过ID删除用户

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **id** | **int64**| 通过ID删除用户 | 

### Return type

 (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **GetUserById**
> User GetUserById(ctx, id)
通过ID获取用户信息

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **id** | **int64**| 通过ID获取用户信息 | 

### Return type

[**User**](User.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **ModifyUser**
> ModifyUser(ctx, user)
修改用户

### Required Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
  **user** | [**User**](User.md)| 修改用户 | 

### Return type

 (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

