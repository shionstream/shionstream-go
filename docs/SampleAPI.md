# \SampleAPI

All URIs are relative to *https://api.gox.my.id*

Method | HTTP request | Description
------------- | ------------- | -------------
[**V1ProtectedSampleGet**](SampleAPI.md#V1ProtectedSampleGet) | **Get** /v1/protected/sample | Protected Sample Endpoint



## V1ProtectedSampleGet

> V1ProtectedSampleGet200Response V1ProtectedSampleGet(ctx).Execute()

Protected Sample Endpoint



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
	resp, r, err := apiClient.SampleAPI.V1ProtectedSampleGet(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SampleAPI.V1ProtectedSampleGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V1ProtectedSampleGet`: V1ProtectedSampleGet200Response
	fmt.Fprintf(os.Stdout, "Response from `SampleAPI.V1ProtectedSampleGet`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiV1ProtectedSampleGetRequest struct via the builder pattern


### Return type

[**V1ProtectedSampleGet200Response**](V1ProtectedSampleGet200Response.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

