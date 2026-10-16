# \AnimeAPI

All URIs are relative to *https://api.gox.my.id*

Method | HTTP request | Description
------------- | ------------- | -------------
[**V1AnimeGet**](AnimeAPI.md#V1AnimeGet) | **Get** /v1/anime | List Anime Catalog
[**V1AnimeSlugGet**](AnimeAPI.md#V1AnimeSlugGet) | **Get** /v1/anime/{slug} | Get Anime Details by Slug



## V1AnimeGet

> V1AnimeGet200Response V1AnimeGet(ctx).Page(page).Limit(limit).Search(search).Type_(type_).Status(status).Genre(genre).Season(season).Year(year).Sort(sort).Execute()

List Anime Catalog



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
	page := "page_example" // string |  (optional) (default to "1")
	limit := "limit_example" // string |  (optional) (default to "20")
	search := "search_example" // string |  (optional)
	type_ := "type__example" // string |  (optional)
	status := "status_example" // string |  (optional)
	genre := "genre_example" // string |  (optional)
	season := "season_example" // string |  (optional)
	year := "year_example" // string |  (optional)
	sort := "sort_example" // string |  (optional) (default to "latest")

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AnimeAPI.V1AnimeGet(context.Background()).Page(page).Limit(limit).Search(search).Type_(type_).Status(status).Genre(genre).Season(season).Year(year).Sort(sort).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AnimeAPI.V1AnimeGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V1AnimeGet`: V1AnimeGet200Response
	fmt.Fprintf(os.Stdout, "Response from `AnimeAPI.V1AnimeGet`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiV1AnimeGetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **page** | **string** |  | [default to &quot;1&quot;]
 **limit** | **string** |  | [default to &quot;20&quot;]
 **search** | **string** |  | 
 **type_** | **string** |  | 
 **status** | **string** |  | 
 **genre** | **string** |  | 
 **season** | **string** |  | 
 **year** | **string** |  | 
 **sort** | **string** |  | [default to &quot;latest&quot;]

### Return type

[**V1AnimeGet200Response**](V1AnimeGet200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V1AnimeSlugGet

> V1AnimeSlugGet200Response V1AnimeSlugGet(ctx, slug).Execute()

Get Anime Details by Slug



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

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AnimeAPI.V1AnimeSlugGet(context.Background(), slug).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AnimeAPI.V1AnimeSlugGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V1AnimeSlugGet`: V1AnimeSlugGet200Response
	fmt.Fprintf(os.Stdout, "Response from `AnimeAPI.V1AnimeSlugGet`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**slug** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiV1AnimeSlugGetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**V1AnimeSlugGet200Response**](V1AnimeSlugGet200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

