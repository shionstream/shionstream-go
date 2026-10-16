# \DashboardAPI

All URIs are relative to *https://api.gox.my.id*

Method | HTTP request | Description
------------- | ------------- | -------------
[**V1DashboardAnimeGet**](DashboardAPI.md#V1DashboardAnimeGet) | **Get** /v1/dashboard/anime | Get Administrative Anime List
[**V1DashboardCategoriesGet**](DashboardAPI.md#V1DashboardCategoriesGet) | **Get** /v1/dashboard/categories | Get Category &amp; Genre Distributions
[**V1DashboardEpisodesGet**](DashboardAPI.md#V1DashboardEpisodesGet) | **Get** /v1/dashboard/episodes | Get Administrative Episodes List
[**V1DashboardModerationGet**](DashboardAPI.md#V1DashboardModerationGet) | **Get** /v1/dashboard/moderation | Get Comment Moderation Reports
[**V1DashboardModerationIdPatch**](DashboardAPI.md#V1DashboardModerationIdPatch) | **Patch** /v1/dashboard/moderation/{id} | Resolve or Dismiss Moderation Report
[**V1DashboardOverviewGet**](DashboardAPI.md#V1DashboardOverviewGet) | **Get** /v1/dashboard/overview | Get Dashboard Overview
[**V1DashboardRolesGet**](DashboardAPI.md#V1DashboardRolesGet) | **Get** /v1/dashboard/roles | Get System Roles &amp; Permissions
[**V1DashboardSeasonsGet**](DashboardAPI.md#V1DashboardSeasonsGet) | **Get** /v1/dashboard/seasons | Get Seasonal Broadcast Distributions
[**V1DashboardStatsGet**](DashboardAPI.md#V1DashboardStatsGet) | **Get** /v1/dashboard/stats | Get Platform Stats
[**V1DashboardUsersGet**](DashboardAPI.md#V1DashboardUsersGet) | **Get** /v1/dashboard/users | Get Users Directory (Admin Only)



## V1DashboardAnimeGet

> V1DashboardAnimeGet200Response V1DashboardAnimeGet(ctx).Page(page).Limit(limit).Status(status).Search(search).Execute()

Get Administrative Anime List



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
	status := "status_example" // string |  (optional)
	search := "search_example" // string |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DashboardAPI.V1DashboardAnimeGet(context.Background()).Page(page).Limit(limit).Status(status).Search(search).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DashboardAPI.V1DashboardAnimeGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V1DashboardAnimeGet`: V1DashboardAnimeGet200Response
	fmt.Fprintf(os.Stdout, "Response from `DashboardAPI.V1DashboardAnimeGet`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiV1DashboardAnimeGetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **page** | **string** |  | [default to &quot;1&quot;]
 **limit** | **string** |  | [default to &quot;20&quot;]
 **status** | **string** |  | 
 **search** | **string** |  | 

### Return type

[**V1DashboardAnimeGet200Response**](V1DashboardAnimeGet200Response.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V1DashboardCategoriesGet

> V1DashboardCategoriesGet200Response V1DashboardCategoriesGet(ctx).Execute()

Get Category & Genre Distributions



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
	resp, r, err := apiClient.DashboardAPI.V1DashboardCategoriesGet(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DashboardAPI.V1DashboardCategoriesGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V1DashboardCategoriesGet`: V1DashboardCategoriesGet200Response
	fmt.Fprintf(os.Stdout, "Response from `DashboardAPI.V1DashboardCategoriesGet`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiV1DashboardCategoriesGetRequest struct via the builder pattern


### Return type

[**V1DashboardCategoriesGet200Response**](V1DashboardCategoriesGet200Response.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V1DashboardEpisodesGet

> V1DashboardEpisodesGet200Response V1DashboardEpisodesGet(ctx).Page(page).Limit(limit).AnimeId(animeId).Execute()

Get Administrative Episodes List



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
	animeId := "animeId_example" // string |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DashboardAPI.V1DashboardEpisodesGet(context.Background()).Page(page).Limit(limit).AnimeId(animeId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DashboardAPI.V1DashboardEpisodesGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V1DashboardEpisodesGet`: V1DashboardEpisodesGet200Response
	fmt.Fprintf(os.Stdout, "Response from `DashboardAPI.V1DashboardEpisodesGet`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiV1DashboardEpisodesGetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **page** | **string** |  | [default to &quot;1&quot;]
 **limit** | **string** |  | [default to &quot;20&quot;]
 **animeId** | **string** |  | 

### Return type

[**V1DashboardEpisodesGet200Response**](V1DashboardEpisodesGet200Response.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V1DashboardModerationGet

> V1DashboardModerationGet200Response V1DashboardModerationGet(ctx).Status(status).Execute()

Get Comment Moderation Reports



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
	status := "status_example" // string |  (optional) (default to "pending")

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DashboardAPI.V1DashboardModerationGet(context.Background()).Status(status).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DashboardAPI.V1DashboardModerationGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V1DashboardModerationGet`: V1DashboardModerationGet200Response
	fmt.Fprintf(os.Stdout, "Response from `DashboardAPI.V1DashboardModerationGet`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiV1DashboardModerationGetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **status** | **string** |  | [default to &quot;pending&quot;]

### Return type

[**V1DashboardModerationGet200Response**](V1DashboardModerationGet200Response.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V1DashboardModerationIdPatch

> V1UserSettingsPatch200Response V1DashboardModerationIdPatch(ctx, id).V1DashboardModerationIdPatchRequest(v1DashboardModerationIdPatchRequest).Execute()

Resolve or Dismiss Moderation Report



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
	v1DashboardModerationIdPatchRequest := *openapiclient.NewV1DashboardModerationIdPatchRequest("Status_example") // V1DashboardModerationIdPatchRequest |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DashboardAPI.V1DashboardModerationIdPatch(context.Background(), id).V1DashboardModerationIdPatchRequest(v1DashboardModerationIdPatchRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DashboardAPI.V1DashboardModerationIdPatch``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V1DashboardModerationIdPatch`: V1UserSettingsPatch200Response
	fmt.Fprintf(os.Stdout, "Response from `DashboardAPI.V1DashboardModerationIdPatch`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiV1DashboardModerationIdPatchRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **v1DashboardModerationIdPatchRequest** | [**V1DashboardModerationIdPatchRequest**](V1DashboardModerationIdPatchRequest.md) |  | 

### Return type

[**V1UserSettingsPatch200Response**](V1UserSettingsPatch200Response.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V1DashboardOverviewGet

> V1DashboardOverviewGet200Response V1DashboardOverviewGet(ctx).Execute()

Get Dashboard Overview



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
	resp, r, err := apiClient.DashboardAPI.V1DashboardOverviewGet(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DashboardAPI.V1DashboardOverviewGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V1DashboardOverviewGet`: V1DashboardOverviewGet200Response
	fmt.Fprintf(os.Stdout, "Response from `DashboardAPI.V1DashboardOverviewGet`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiV1DashboardOverviewGetRequest struct via the builder pattern


### Return type

[**V1DashboardOverviewGet200Response**](V1DashboardOverviewGet200Response.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V1DashboardRolesGet

> V1DashboardRolesGet200Response V1DashboardRolesGet(ctx).Execute()

Get System Roles & Permissions



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
	resp, r, err := apiClient.DashboardAPI.V1DashboardRolesGet(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DashboardAPI.V1DashboardRolesGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V1DashboardRolesGet`: V1DashboardRolesGet200Response
	fmt.Fprintf(os.Stdout, "Response from `DashboardAPI.V1DashboardRolesGet`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiV1DashboardRolesGetRequest struct via the builder pattern


### Return type

[**V1DashboardRolesGet200Response**](V1DashboardRolesGet200Response.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V1DashboardSeasonsGet

> V1DashboardSeasonsGet200Response V1DashboardSeasonsGet(ctx).Execute()

Get Seasonal Broadcast Distributions



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
	resp, r, err := apiClient.DashboardAPI.V1DashboardSeasonsGet(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DashboardAPI.V1DashboardSeasonsGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V1DashboardSeasonsGet`: V1DashboardSeasonsGet200Response
	fmt.Fprintf(os.Stdout, "Response from `DashboardAPI.V1DashboardSeasonsGet`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiV1DashboardSeasonsGetRequest struct via the builder pattern


### Return type

[**V1DashboardSeasonsGet200Response**](V1DashboardSeasonsGet200Response.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V1DashboardStatsGet

> V1DashboardStatsGet200Response V1DashboardStatsGet(ctx).Execute()

Get Platform Stats



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
	resp, r, err := apiClient.DashboardAPI.V1DashboardStatsGet(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DashboardAPI.V1DashboardStatsGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V1DashboardStatsGet`: V1DashboardStatsGet200Response
	fmt.Fprintf(os.Stdout, "Response from `DashboardAPI.V1DashboardStatsGet`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiV1DashboardStatsGetRequest struct via the builder pattern


### Return type

[**V1DashboardStatsGet200Response**](V1DashboardStatsGet200Response.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V1DashboardUsersGet

> V1DashboardUsersGet200Response V1DashboardUsersGet(ctx).Page(page).Limit(limit).Role(role).Search(search).Execute()

Get Users Directory (Admin Only)



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
	role := "role_example" // string |  (optional)
	search := "search_example" // string |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DashboardAPI.V1DashboardUsersGet(context.Background()).Page(page).Limit(limit).Role(role).Search(search).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DashboardAPI.V1DashboardUsersGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V1DashboardUsersGet`: V1DashboardUsersGet200Response
	fmt.Fprintf(os.Stdout, "Response from `DashboardAPI.V1DashboardUsersGet`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiV1DashboardUsersGetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **page** | **string** |  | [default to &quot;1&quot;]
 **limit** | **string** |  | [default to &quot;20&quot;]
 **role** | **string** |  | 
 **search** | **string** |  | 

### Return type

[**V1DashboardUsersGet200Response**](V1DashboardUsersGet200Response.md)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

