# \SystemAPI

All URIs are relative to *https://api.gox.my.id*

Method | HTTP request | Description
------------- | ------------- | -------------
[**HealthGet**](SystemAPI.md#HealthGet) | **Get** /health | Health Check



## HealthGet

> HealthGet200Response HealthGet(ctx).Execute()

Health Check



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
	resp, r, err := apiClient.SystemAPI.HealthGet(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SystemAPI.HealthGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `HealthGet`: HealthGet200Response
	fmt.Fprintf(os.Stdout, "Response from `SystemAPI.HealthGet`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiHealthGetRequest struct via the builder pattern


### Return type

[**HealthGet200Response**](HealthGet200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

