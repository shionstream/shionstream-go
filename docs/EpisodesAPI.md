# \EpisodesAPI

All URIs are relative to *https://api.gox.my.id*

Method | HTTP request | Description
------------- | ------------- | -------------
[**V1AnimeSlugEpisodesGet**](EpisodesAPI.md#V1AnimeSlugEpisodesGet) | **Get** /v1/anime/{slug}/episodes | List Episodes by Anime Slug
[**V1EpisodesIdStreamGet**](EpisodesAPI.md#V1EpisodesIdStreamGet) | **Get** /v1/episodes/{id}/stream | Get Episode Stream Sources



## V1AnimeSlugEpisodesGet

> V1AnimeSlugEpisodesGet200Response V1AnimeSlugEpisodesGet(ctx, slug).Page(page).Limit(limit).Sort(sort).Execute()

List Episodes by Anime Slug



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
	slug := "slug_example" // string | 
	page := "page_example" // string |  (optional) (default to "1")
	limit := "limit_example" // string |  (optional) (default to "50")
	sort := "sort_example" // string |  (optional) (default to "asc")

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.EpisodesAPI.V1AnimeSlugEpisodesGet(context.Background(), slug).Page(page).Limit(limit).Sort(sort).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `EpisodesAPI.V1AnimeSlugEpisodesGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V1AnimeSlugEpisodesGet`: V1AnimeSlugEpisodesGet200Response
	fmt.Fprintf(os.Stdout, "Response from `EpisodesAPI.V1AnimeSlugEpisodesGet`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**slug** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiV1AnimeSlugEpisodesGetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **page** | **string** |  | [default to &quot;1&quot;]
 **limit** | **string** |  | [default to &quot;50&quot;]
 **sort** | **string** |  | [default to &quot;asc&quot;]

### Return type

[**V1AnimeSlugEpisodesGet200Response**](V1AnimeSlugEpisodesGet200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V1EpisodesIdStreamGet

> V1EpisodesIdStreamGet200Response V1EpisodesIdStreamGet(ctx, id).Execute()

Get Episode Stream Sources



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

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.EpisodesAPI.V1EpisodesIdStreamGet(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `EpisodesAPI.V1EpisodesIdStreamGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V1EpisodesIdStreamGet`: V1EpisodesIdStreamGet200Response
	fmt.Fprintf(os.Stdout, "Response from `EpisodesAPI.V1EpisodesIdStreamGet`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiV1EpisodesIdStreamGetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**V1EpisodesIdStreamGet200Response**](V1EpisodesIdStreamGet200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

