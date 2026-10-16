# \CommentsAPI

All URIs are relative to *https://api.gox.my.id*

Method | HTTP request | Description
------------- | ------------- | -------------
[**V1CommentsGet**](CommentsAPI.md#V1CommentsGet) | **Get** /v1/comments | Get Episode Comments
[**V1CommentsIdLikePost**](CommentsAPI.md#V1CommentsIdLikePost) | **Post** /v1/comments/{id}/like | Like or Dislike Comment
[**V1CommentsIdReportPost**](CommentsAPI.md#V1CommentsIdReportPost) | **Post** /v1/comments/{id}/report | Report Comment
[**V1CommentsPost**](CommentsAPI.md#V1CommentsPost) | **Post** /v1/comments | Create Comment



## V1CommentsGet

> V1CommentsGet200Response V1CommentsGet(ctx).EpisodeId(episodeId).Execute()

Get Episode Comments



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/shionstream/shionstream-go"
)

func main() {
	episodeId := "episodeId_example" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CommentsAPI.V1CommentsGet(context.Background()).EpisodeId(episodeId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CommentsAPI.V1CommentsGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V1CommentsGet`: V1CommentsGet200Response
	fmt.Fprintf(os.Stdout, "Response from `CommentsAPI.V1CommentsGet`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiV1CommentsGetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **episodeId** | **string** |  | 

### Return type

[**V1CommentsGet200Response**](V1CommentsGet200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V1CommentsIdLikePost

> V1CommentsIdLikePost200Response V1CommentsIdLikePost(ctx, id).V1CommentsIdLikePostRequest(v1CommentsIdLikePostRequest).Execute()

Like or Dislike Comment



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/shionstream/shionstream-go"
)

func main() {
	id := "id_example" // string | 
	v1CommentsIdLikePostRequest := *openapiclient.NewV1CommentsIdLikePostRequest() // V1CommentsIdLikePostRequest |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CommentsAPI.V1CommentsIdLikePost(context.Background(), id).V1CommentsIdLikePostRequest(v1CommentsIdLikePostRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CommentsAPI.V1CommentsIdLikePost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V1CommentsIdLikePost`: V1CommentsIdLikePost200Response
	fmt.Fprintf(os.Stdout, "Response from `CommentsAPI.V1CommentsIdLikePost`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiV1CommentsIdLikePostRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **v1CommentsIdLikePostRequest** | [**V1CommentsIdLikePostRequest**](V1CommentsIdLikePostRequest.md) |  | 

### Return type

[**V1CommentsIdLikePost200Response**](V1CommentsIdLikePost200Response.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V1CommentsIdReportPost

> V1CommentsIdLikePost200Response V1CommentsIdReportPost(ctx, id).V1CommentsIdReportPostRequest(v1CommentsIdReportPostRequest).Execute()

Report Comment



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/shionstream/shionstream-go"
)

func main() {
	id := "id_example" // string | 
	v1CommentsIdReportPostRequest := *openapiclient.NewV1CommentsIdReportPostRequest("Reason_example") // V1CommentsIdReportPostRequest |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CommentsAPI.V1CommentsIdReportPost(context.Background(), id).V1CommentsIdReportPostRequest(v1CommentsIdReportPostRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CommentsAPI.V1CommentsIdReportPost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V1CommentsIdReportPost`: V1CommentsIdLikePost200Response
	fmt.Fprintf(os.Stdout, "Response from `CommentsAPI.V1CommentsIdReportPost`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiV1CommentsIdReportPostRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **v1CommentsIdReportPostRequest** | [**V1CommentsIdReportPostRequest**](V1CommentsIdReportPostRequest.md) |  | 

### Return type

[**V1CommentsIdLikePost200Response**](V1CommentsIdLikePost200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V1CommentsPost

> V1CommentsPost201Response V1CommentsPost(ctx).V1CommentsPostRequest(v1CommentsPostRequest).Execute()

Create Comment



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/shionstream/shionstream-go"
)

func main() {
	v1CommentsPostRequest := *openapiclient.NewV1CommentsPostRequest("AnimeId_example", "EpisodeId_example", "Content_example") // V1CommentsPostRequest |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CommentsAPI.V1CommentsPost(context.Background()).V1CommentsPostRequest(v1CommentsPostRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CommentsAPI.V1CommentsPost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V1CommentsPost`: V1CommentsPost201Response
	fmt.Fprintf(os.Stdout, "Response from `CommentsAPI.V1CommentsPost`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiV1CommentsPostRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **v1CommentsPostRequest** | [**V1CommentsPostRequest**](V1CommentsPostRequest.md) |  | 

### Return type

[**V1CommentsPost201Response**](V1CommentsPost201Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

