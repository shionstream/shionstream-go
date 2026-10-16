# \UploadAPI

All URIs are relative to *https://api.gox.my.id*

Method | HTTP request | Description
------------- | ------------- | -------------
[**V1UploadHlsPost**](UploadAPI.md#V1UploadHlsPost) | **Post** /v1/upload/hls | Upload HLS Package to Cloudflare R2
[**V1UploadImagePost**](UploadAPI.md#V1UploadImagePost) | **Post** /v1/upload/image | Upload Image to Cloudflare R2



## V1UploadHlsPost

> V1UploadHlsPost200Response V1UploadHlsPost(ctx).Execute()

Upload HLS Package to Cloudflare R2



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

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.UploadAPI.V1UploadHlsPost(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `UploadAPI.V1UploadHlsPost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V1UploadHlsPost`: V1UploadHlsPost200Response
	fmt.Fprintf(os.Stdout, "Response from `UploadAPI.V1UploadHlsPost`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiV1UploadHlsPostRequest struct via the builder pattern


### Return type

[**V1UploadHlsPost200Response**](V1UploadHlsPost200Response.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V1UploadImagePost

> V1UploadImagePost200Response V1UploadImagePost(ctx).Execute()

Upload Image to Cloudflare R2



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

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.UploadAPI.V1UploadImagePost(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `UploadAPI.V1UploadImagePost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V1UploadImagePost`: V1UploadImagePost200Response
	fmt.Fprintf(os.Stdout, "Response from `UploadAPI.V1UploadImagePost`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiV1UploadImagePostRequest struct via the builder pattern


### Return type

[**V1UploadImagePost200Response**](V1UploadImagePost200Response.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

